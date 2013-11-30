Little Heathens Jams Site Root
----
These files were created using Yeoman and the [angular-generator-fullstack](https://github.com/DaftMonk/generator-angular-fullstack) generator

### Express

Launch your express server in development mode.
```
grunt serve
```

Launch your express server in production mode, uses the minified/optimized production app folder.
```
grunt serve:dist
```

### Livereload

`grunt serve` will watch client files in `app/`, and server files inside `lib/`, restarting the Express server when a change is detected.

### Deployment

After modifying the app: `grunt heroku` to rebuild the deployment folder

Push the updates to github: `cd heroku && git push heroku master`

Type `heroku open` to view updated app
