

## 🚀 Task 1 – CI/CD Pipeline with GitHub Actions

This project is a part of a DevOps internship task to automate code deployment using a CI/CD pipeline.  
I used **GitHub Actions** to create a pipeline that automatically runs tests, builds a Docker image, and pushes it to **DockerHub** when I push code to the `main` branch.

### 🔧 Tools Used
- Node.js  
- GitHub & GitHub Actions  
- Docker & DockerHub

### 📁 What I Did
- Cloned a sample Node.js app
- Created a GitHub Actions workflow file in `.github/workflows/main.yml`
- Set up CI/CD steps: install → test → build Docker image → push to DockerHub
- Used GitHub Secrets to store DockerHub credentials securely


**For the most up to date test app to get you started on Heroku, head on over to [`node-js-getting-started`](https://github.com/heroku/node-js-getting-started).**

---

# node-js-sample

A barebones Node.js app using [Express 4](http://expressjs.com/).

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
git clone git@github.com:heroku/node-js-sample.git # or clone your own fork
cd node-js-sample
npm install
npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
heroku create
git push heroku master
heroku open
```

Alternatively, you can deploy your own copy of the app using the web-based flow:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [10 Habits of a Happy Node Hacker](https://blog.heroku.com/archives/2014/3/11/node-habits)
- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)
