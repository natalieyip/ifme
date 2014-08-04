if me
=====

An open-source community for mental health experiences

Getting started
---------------

Easiest ways to install Ruby on Rails and Postgres:

http://railsinstaller.org/en

http://www.postgresql.org/download/

After cloning the app on your local machine, in your terminal run the following commands to get it up and running:

```
bundle install
```

```
sudo su - postgres
```

```
createuser -s -r juria
````

```
bin/rake db:create db:migrate
```

```
rails s
```

Testing accounts
-----------------

They have been created in seeds.rb

```
Email: test1@example.com
Password: password99
```

```
Email: test2@example.com
Password: password99
```

Rspec tests
------------

```
rspec
```


