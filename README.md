### Spring Boot Heroku

A simple app to demo publishing a Spring Boot application to Heroku

Authenticate with Heroku:

``` heroku login```

Create the app:

``` heroku create```

Add the Heroku origin if it hasn't already been added:

```heroku git:remote -a {container-name}```

Push to Heroku:

```git push heroku master```

Open the app:

```heroku open```

Profit.