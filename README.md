# Message-Board
Small Ruby on Rails project that allows its user to post and comment messages on a custom board. 
Certain functionalities, such as edit and delete messages and comments, are only available by sign in authentication. With that, the only user allowed to edit or delete is the respective creator of the targeted message or comment.

### Gems used
* [Devise](https://rubygems.org/gems/devise)
* [Bootstrap_sass](https://rubygems.org/gems/bootstrap-sass)
* [Simple_form](https://rubygems.org/gems/simple_form)
_______________________________________________________________
### What i learned with this project
* How to implement user registration, session and authentication on Rails app;
* How to behave the app accordingly to current user session;
* How to use simple_form gem to build forms;
* How to use partials and how to make use of them in different pages throughout the application.

### Try it yourself
* Clone or download the repository .zip and then run ```bundle install``` in project directory via terminal to fetch all the needed gems.
* Still in the project directory, run the ```rails server``` or ```rails s``` command via terminal to boot up the rails server;
* Access the app on http://localhost:3000/ address in your browser.
