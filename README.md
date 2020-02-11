# freeBuddy

clone the repo
``` 
git clone git@github.com:nitanshu/freeBuddy.git
bundle install
```
Create a .env file copy the content from .env.template 

Enable google calendar API and create the credentials for google calendar.
 
To create credentials for google calendar please insert these uris in Oauth Consent screen
 
Authorized JavaScript origins
```
 http://localhost:3000 in auhtorized origin
```

Authorized redirect URIs

```
http://localhost:3000/users/auth/google_oauth2/callback 
```

