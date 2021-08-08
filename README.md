# Node Hello World

Simple node.js app that servers "hello world"

Great for testing simple deployments to the cloud

## Run It

`npm start`

## Run in Docker

```bash
docker build -t node-hello .            #build image
docker run -it -p 9000:3000 node-hello  #start instance on port 9000
```
