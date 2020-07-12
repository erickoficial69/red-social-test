# imgShare
imgShare is a web application to share images, comments, and more.

![](docs/screenshot1.png)
# Demo
https://red-social-test.herokuapp.com/

# Environment Variables
* `MONGODB_URI`, the mongodb database uri
* `PORT` the http server port. By default is `3000`

# Installation
```
git clone https://github.com/erickoficial69/red-social-test
cd red-social-test
npm install 
npm start
```

# Docker
```
docker-compose build
```
```
docker-compose up
```

# Improvements for the Future
- Input Validation (to avoid XSS)
- User Authentication