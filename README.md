# Beginner's Guide to Web Development
### HTML + CSS Fundamentals Course
###### Rodgers M Gitau (2017)

----

#### Lesson One

**Q1: How do Browsers Work?** 
[Source](https://www.quora.com/How-does-a-browser-work)

A browser does a lot of things nowadays (chrome runs apps, for example), but I think you are interested in knowing how a web page is loaded and displayed.

First, need to explain that the Web is a client/server application. The browser is just half of it (the client). In the other side there must be a web server waiting for requests, which is the other half of the application.

First the browser has to find the IP address of the web server. It asks the Operating System (OS) to translate the server name. The OS uses it's local cache or the DNS server if the address it's not known yet.

After finding the IP address, the browser sends an HTTP request to the server requesting the appropriate file (web page). If no file was specified, the server responds with the "default file" (index.html, index.php, index.asp or any other that is configured in the web server). For regular web browsing, the file will be a text file formatted in HTML. But it may be any kind of file.

After getting the requested file, the browser has two things to do: interpret and render the HTML page, and obtain the remaining objects (images, flash files, javascript files, css files, audio, video, etc.) and interpret and display them.

Some browsers will begin to interpret and render the HTML file immediately and request the objects in parallel, filling in the objects as they are received. Others will wait to received all objects and, just then, will render and display the HTML file.

That's it. The browser will then rest waiting the user to request another file to begin everything again.


