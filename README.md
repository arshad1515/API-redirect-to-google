# API-redirect-to-google

var http = require("http");

http.createServer(function(req, res) {
  res.writeHead(301,{Location: 'https://www.google.com/'});
  res.end();
}).listen(8888);
