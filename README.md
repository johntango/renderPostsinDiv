# renderPostsinDiv
This contains two different demos
1) index0.html gets data from local file posts.js
2) index.html gets data from Amazon Web Server using fetch

To access Amazon Web Server we need to run a local web server using http-server in the same directory as index.html.  The web-server usually runs on localhost:8080  so by going in the browser to http://localhost:8080  you will get index.html by default.  It then will go out to the Amazon Web server and get the file .../posts.json

Ignore the file puppet.js for now