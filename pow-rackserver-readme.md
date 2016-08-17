# Pow Ruby Rack Server

![Pow icon](http://pow.cx/images/logo-pow.png)

**Pow** is a zero-config Rack server for Mac OS X. Have it serving your ruby rack apps locally in under a minute. It is compatible with rbenv automatically and no additional step is required.


#### Configure a rack microservice application
Let's say you're working on an app that lives in ~/Dev/datapipe-awesome-app. You'd like to access it at http://datapipe-awesome-app.dev/.Setting it up is as easy as
to add a symlink of your app root folder into ~/.pow

```
cd ~/.pow
ln -s /path/to/myapp
```
That’s it! Your app will be up and running at ```http://datapipe-awesome-app.dev/```

#### Extended instructions
<http://pow.cx/manual.html#section_2.3.1>
