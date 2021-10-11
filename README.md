# RESTAURANT-CSS-FRAMEWORK

[Curry Paradise](https://thomasmelchers.github.io/restaurant-css-framework/index.html)

## Curry Paradise
Building a restaurant **Curry Paradise** web page with the framework Bootstrap 5 (latest edition). The goal of this exercice is to discover how to use Bootstrap and how to integrate some of its components. This website has been developed with a mobile-first approach and it is responsive for tablet and computer. 

### Theme 
I create an imaginary restaurant for this exercice. It is focused on the Sri Lankan gastronomy.

## Instructions to create the website

Here are the [instructions](https://github.com/becodeorg/BXL-Swartz-5.34/blob/main/1.The-Field/10.Bootstrap/README.adoc) that I have to follow for that exercice. 


## Building the website

### Languages used
* HTML
* CSS
* BOOTSTRAP Framework - v5.1 latest edition in 2021 October

### Structure

#### Structure of the website
I create 5 HTML pages
* index.html // Welcome page
* menu.html
* pictures.html and the three others to host the other images.
* restaurant.html
* contact.html

Each page has been established on the same structure : a navigation bar on top, a jumbotron and a footer ont the bottom. At the back of the navigation bar and the jumbotron component there is a background image which will be different on every pages (excepted on the 4 pictures pages). Under the jumbotron, there will be places to host other components that will be displayed on the different pages. 

* **On the *menu page*:**
The content of the page is about the menu of the restaurant.
There is a list-group component which has been used to establish the menu. Some badges have been setled up next to some meals. The badge has the mission to show which of the meals are vegan. 

* **On the *pictures page*:**
The content of the page is to show some pictures of the restaurant. Because it is a fake one, I will show only some meals' pictures.
There will be displayed three by page and there will nested in a card component. Every card component will show on the top part the picture and then bellow a description of it. 
To navigate between the different pictures pages, a pagination component will be displayed under the card.

* **On the *restaurant page*:**
The content of the page is to show so details about the restaurant. Location, accessibility, map and the schedules.
Each information has been nested in a special column of a general grid which easily makes the design responsive.

* **On the **contact page*:***
The role of this page is to create a form like this the clients can be in touch with the restaurant. We have several required fields (Firstname, Name, Email, Subject and a text area). We used a dropdown list to show the different subject options. 


#### Style sheets
I create a file *style.css* where I write all the code which will affect the style of every pages. So in this file we will have the style for : 
* Navigation bar;
* Jumbotron component and its buttons;
* Footer ;
* The background gradient ;
* The font-family. 

Then each html *page will* be linked to a special *css file* (named as the name of the html file) which will contain all the respective code which is only present on it as
* The special background image;
* The colors;
* The style of the buttons;
* The text & titles styles;
* Some padding and margin.

## RESSOURCES

### FONTS
I use one different fonts I pick on google fonts : 
* [Kalam](https://fonts.google.com/specimen/Kalam?query=kalam)
* a sans-serif font will be displayed if the 'kalam font' doesn't work.

### ICONS
There are coming from font awesome
[fontawesome](https://fontawesome.com/)

### PICTURES
I have chosen pictures from two different sources. One is roality-free and the other one not, this is my bad. It try to change it all to royality-free, I've done my best. 
* the background pictures are coming from [Unsplash](unsplash.com);
* the pictures of the meals are coming from [Cuisinez sri lankais](https://www.instagram.com/cuisinezsrilankais/?hl=fr);
