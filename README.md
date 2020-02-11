# README

### Project : DRIBBLE CLONE APP

#### Ready to deploy it in HEROKU

*  First Steps :

```
  - Added Gems in gemfile;
  - guard init livereload;
  - bundle exec guard;
  - rails generate simple_form:install;
  - rails g devise:install  ;
  - rails g controller home index;
  - rails g devise:views;
  - rails g devise User;
  - rails db:migrate;
  - rails g migration AddFieldsToUsers name:string;
  - rails g scaffold Shot title:string description:text user_id:integer;
  - rails db:migrate;
  - rails c ( User.connection;@user = User;@user.last;@user = @user.last;@user.destroy;  )
  -  rails g uploader Shot; - delete this file.
  - rails g uploader user_shot;
  - rails g migration add_user_shot_to_shots ;
  - rails db:migrate;
  - 

```