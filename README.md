# gaecdn

Use the Google App Engine as small CDN host for your static files like images, styles and scripts. Example configuration have following folder structure.

    /assets
        /css
        /images
        /scripts

Edit the app.yaml file and replace the app-id with your application id. When deployed can you use your App Engine CDN like this.

    http://<app-id>.appspot.com/css/style.css