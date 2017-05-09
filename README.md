# starter express app template

* node with babel
* expressjs
* airbnb eslint rules

Procfile set up to run on [heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs#deploy-the-app)

## Notes:
* Assignment description: [assignment](http://cs52.me/assignments/sa/server-side/)
* App is running on: [link](https://cs52-sa7-jinnan.herokuapp.com/)
* Github link: [github link](https://git.heroku.com/cs52-sa7-jinnan.git)

## Deploy to Heroku

Download and install the Heroku CLI.

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.
```
$ heroku login
```

Clone the repository

Use Git to clone cs52-sa7-jinnan's source code to your local machine.
```
$ heroku git:clone -a cs52-sa7-jinnan
$ cd cs52-sa7-jinnan
```
Deploy your changes

Make some changes to the code you just cloned and deploy them to Heroku using Git.

```
$ git add .
$ git commit -am "make it better"
$ git push heroku master
```
