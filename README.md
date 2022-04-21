# Dino-Introduction
Just T-rex chrome dino game on Chrome.
# How to use index.html
"index.html" is the main file. 
You need to install HTTP server before using it：

npm install http-server

Switch to the directory where "index.html" is located, and then start httpserver in the current directory:

http-server 8080

At this point, open your browser and enter the URL：

127.0.0.1:8080

# How to use dino.js
First, download "dino.js" to your computer or upload to your server.

Second,add "<script src=[dino.js's path]></script>" to your webpage "<head>" label.

Example:
<code><script src="gaozixuan0213.github.io/dino/dino.js"></script></code>

Run:
<code><script>initRunner( '#[canvas_name]' );</script></code>
