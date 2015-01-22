## Steps to make a new rails hello world app.
**(when you see [] that means replace what I wrote with your input)**
**(when you see $ that means enter this as a command line command)**

1. open a terminal and go to the place where you want to make your new app

2. type 
  > $ rails new [App_Name]  
then
  > $ bundle install

3. go to ROOT/config/routes.rb and make a root route which goes to a controller and method you want it to go to.
  remember the routes syntax is 'whatever' to => '[controller]#[controllerMethod]'. this file has examples in it as comments

4. make a controller with a name that matches the controller name from your route. you can do this with
  > $ rails generate controller [name] 
or you can make it manually

5. make a method in your controller whose name matches the method part of the route you made (ie controller#method from the routes file)

6. make a folder under the ROOT/app/views/ directory which matches the name of your new controller.

7. make a view in that folder whose name is [controllerMethod].html.erb. ControllerMethod should match the name of the method from your controller and the name from your route

8. write your html in the view

9. Go to the command line and enter
  > $ rails server 
or for short
  > $ rails s

10. Checkout out localhost:3000 in your browser and you should see your html
