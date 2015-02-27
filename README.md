# gaecdn

Use the Google App Engine as small CDN host for your static files like images, styles and scripts.  
This example have the following folder structure.

    /assets
        /css
            style.css
        /images
            appengine.gif
        /scripts
            jquery-1.11.2.min.js

Edit the app.yaml file and replace the app-id with your application id and deploy your files.  

    http://<app-id>.appspot.com/css/style.css
    http://<app-id>.appspot.com/images/appengine.gif
    http://<app-id>.appspot.com/scripts/jquery-1.11.2.min.js

## Feedback
Star this repo if you found it useful. Use the github issue tracker to give feedback on this repo.