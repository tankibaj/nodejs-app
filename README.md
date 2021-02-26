## Nodejs app
The repository contains a simple node.js app which generates a web page with the nodejs official logo. I use this app to test CI/CD pipeline.


#### NPM

`npm install`

`npm start`


#### Docker

```bash
docker build --tag nodejs-app .
```

```bash
docker run -d --rm -p 3000:3000 nodejs-app
```