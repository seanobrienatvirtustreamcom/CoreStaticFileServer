# CoreStaticFileServer
Simple .NET Core web server with MVC and Static Files to test CF compatibility

## Changes
Made changes to Program.cs to support command line argument configuration

Locally the solution can serve MVC and static files
http://localhost:5000/ <- shows /home/
http://localhost:5000/statictest.html <- shows Static File middleware working

neither seems to work upon a push to Bluemix
