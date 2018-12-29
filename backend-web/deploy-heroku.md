# how to deploy a node app to heroku 

## Reminders 

make sure to  create a port variable and set it to 

` const post = process.env.PORT || 3000;`

Make sure to have a start script inside your package.json file  ``` 
"scripts": {
    "start": "nodemon server.js"
  }, ```

you also want to specify what version of node you are using  ``` "engines": {
    "node": "10.x"
  } ```


  ## Steps to deploy 

  1. using your terminal login to heroku `$ heroku login`

  2. run `$ heroku create` in the terminal

  3. run `$ git push heroku master`


## Setting up ApiKey with Heroku

``` $heroku config:set API_KEY_NAME="string" ```

## change Git repo heroku

``` $git remote set-url heroku https://git.heroku.com/keyology.git
 ```



