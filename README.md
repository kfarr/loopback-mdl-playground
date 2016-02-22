# loopback-mdl-playground

I've been impressed with the Node.js framework [Loopback](http://loopback.io/), including their great docs with this [tutorial project to create a basic Yelp clone](https://docs.strongloop.com/display/public/LB/Introducing+the+Coffee+Shop+Reviews+app). But the result of the tutorial looks very plain and could use a number of improvements. Here's a screenshot of the original styling:

<img src="https://docs.strongloop.com/download/attachments/5309491/coffee-shop-reviews-home.png?version=1&modificationDate=1421278616000&api=v2" width="400">

This repo gives the Loopback tutorial a "facelift" by restyling with the [Material Design Lite (MDL)](https://www.getmdl.io/) library. MDL is a nifty CSS library that offers a very simple and effective implementation of [Google's Material Design](https://www.google.com/design/spec/material-design/introduction.html), allowing a beginner to quickly style a site according to Material Design standards.

Here's a screenshot of the improved styling with Material Design Lite
![Screenshot](screenshot.png?raw=true "Screenshot")

# Requirements
Most of the dependencies can be found in the package.json file. However, you will also need to have local instances of MySQL and MongoDB setup and then modify appropriate Loopback/node database config settings to make this work. For more info on this, reference the original [Loopback coffee shop tutorial docs](https://docs.strongloop.com/display/public/LB/Introducing+the+Coffee+Shop+Reviews+app).

# ToDo
* Left / mobile nav is not "hooked up"
* Responsive issues
* Not all pages are styled with MDL yet
* Auth validation error messages
