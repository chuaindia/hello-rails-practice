# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...




Looking at the output of the command you will see all the generated things, but for now you only need to focus on one app/views/pages/hello.html.erb. You will put your HTML in this one.
Open the file app/views/pages/hello.html.erb and add an h1 element saying "Hello world".
Open http://localhost:3000/pages/hello in your browser. You should see your "Hello world" message.
In config/routes.rb replace get 'pages#hello' with root 'pages#hello'
Revisit http://localhost:3000/ and see your changes in action. Now your "Hello world" page should be displayed as the main page.
Push all your changes to GitHub.