# LA Rails Learners

## First App

### Phase One

    $ rails new myapp --database=postgresql

    $ rake db:setup

      newspaper_app_development already exists
      newspaper_app_test already exists
      /vagrant/newspaper_app/db/schema.rb doesn't exist yet. 

      Run `rake db:migrate` to create it, then try again. 

      If you do not intend to use a database, you should instead alter /vagrant/newspaper_app/config/application.rb to limit the frameworks that will be loaded.

    $ rake db:migrate

    $ rake db:setup
      newspaper_app_development already exists
      newspaper_app_test already exists
      -- enable_extension("plpgsql")
       -> 0.0822s
      -- initialize_schema_migrations_table()
       -> 0.0550s
      -- enable_extension("plpgsql")
      -> 0.1057s
     -- initialize_schema_migrations_table()
     -> 0.0290s

    $ rails g scaffold User first_name:string last_name:string email:string

    $ rake db:migrate

    $ git init

    $ git remote add origin git@github.com:LARailsLearners/your_app.git

-----
