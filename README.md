#Primer Repo en GitHub
#Hola mundo en experess 

const http = require('http');

const server = http.createServer((req, res) => {
    res.status = 200;
    res.setHeader('Content-Type', 'text/plain');
    res.end('Hello World');
});

server.listen(3000, () => {
    console.log('Server on port 3000');
});
