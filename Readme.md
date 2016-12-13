## Friendface requires a free oauth server.  oauth.io no longer has a permanent free tier.

#What is Friendface?

Thank you to the show *The IT Crowd* for the name.
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/6rNgCnY1lPg/0.jpg)](http://www.youtube.com/watch?v=6rNgCnY1lPg)

Basically github is a social network without some of the most simple social features.
This repo is just a view of the social network already available on github using gists as posts.

#Fork Your Own

1) Fork this project.

2) Make sure to work on the gh-pages branch.

3) Go to oauth.io and get your Public Key.
Set your oauth.io Public Key inside the index.html file.
```
OAuth.initialize('your oauth.io Public Key');
```

4) Go to your Github user -> Edit Profile -> Applications -> Developer Applications -> Register new Application

Now keep that window open and go to oauth.io -> Integrated APIs -> Add APIs -> github.

Follow the instructions :)

Also remember to add your url http://yourusername.github.io/FriendFace/ to the Domains & URLs whitelist on your oauth.io account.

5) Go to your site http://yourusername.github.io/FriendFace/
