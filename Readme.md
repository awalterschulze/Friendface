#What is Friendface?

https://www.youtube.com/watch?v=6rNgCnY1lPg
Thank you to the show The IT Crowd for the name.

Basically github is a social network without any social features.
This repo is just a view of the social network already available on github using gists as posts.

#Fork Your Own

1) Fork this project.

2) Go to oauth.io and get your Public Key.
Set your oauth.io Public Key inside the index.html file.
```
OAuth.initialize('your oauth.io Public Key');
```

3) Go to your Github user -> Edit Profile -> Applications -> Developer Applications -> Register new Application
Now keep that window open and go to oauth.io -> Integrated APIs -> Add APIs -> github.
Follow the instructions :)
Also remember to add your url http://awalterschulze.github.io/feed/ to the Domains & URLs whitelist on your oauth.io account.