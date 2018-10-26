var http = require('http');

var hostname = '127.0.0.1';
var port = 8081;

var server = http.createServer(function(reg,res){
res.statusCode = 200;
res.setHeader('Content-Type' , 'text/plain');
res.end('Hello Advance web class \n';
});
server.listen(port, hostname);
console.log("server running at http://" + hostname + ":" + port);
