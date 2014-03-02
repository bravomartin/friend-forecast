# Hats
Guest Lecture at Craig Protzel's class Mashups: Creating with Web API's
NYU ITP Spring 2014

By: Martin Bravo
Email: [bravomartin@gmail.com](mailto:bravomartin@gmail.com)
URL: [bravomartin.cl](http://bravomartin.cl)


## Example: Friends Forecast

To run the example you'll need a facebook App ID:

* Log in to [Facebook Developers] (https://developers.facebook.com/) 
* Create a new app
* Copy the App ID, replace the id in the js file


To be able to test locally, you need to do a trick to get around facebook API authorization requirement for having a public domain.

Add a fake domain alias to localhost in `/etc/hosts`

```
sudo vim /etc/hosts
```

At the end of the file, add:

```
172.0.0.1   development.dev
```

And in the app's settings in Facebook, add a Platform, select Website and input the Site URL `http://development.dev/`

Then in your project folder in Terminal, run;

```
sudo php -S development.dev:80
```
You'll need PHP 5.4+ (comes with Mavericks and Mountain Lion)




##How to use this example

This example has 3 parts:

* `/01` has some tests to go over the data.
* `/02` is a direct download from HTML Boilerplate.
* `/03` is the full example.

During the class we will play around with the data in `/01`, and build `/02` using parts from `/03`.




