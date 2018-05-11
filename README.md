# Financial Web Application

This is a simple Web application that fetches some financial information about a company and shows in a organised
structure.

## Objective

The main goal of this web app is to serve as an example for beginners, showing simple ways to use some of the most used
tools in web development scene.

## Motivation
The motivation to build this example comes from the creator's experience in teaching web development introductory
courses on undergraduate level that created a urge for motivate the students to be proactive and learn by themselves,
outside the class.

## Improvement suggestions

* ~~Let the user searches using the company's name instead of its symbol~~
* ~~Fix the news section error that appends news on each company search~~
* Better alignment of company's logo
* Allow the users to search when they press the ```Enter``` key (HINT: use the ```<form>``` tag or add a event listener)
for the ```Enter``` key)
* Handle each AJAX error in a different way based on its content. For instance, the AJAX query that fetches the
company's CEO must be handled differently than the AJAX query that fetches data to plot the chart
* Play along with Bootstrap components for better aesthetic

## Live Instance

You can see a functional version of this app on [JSFiddle](https://jsfiddle.net/jpmoura/5u0st8h4/).

## Build on top of

* [Bootstrap 4.1.1](https://getbootstrap.com/)
* [jQuery 3.3.1](https://jquery.com/)
* [IEX API](https://iextrading.com/developer/docs/)
* [Google Charts](https://developers.google.com/chart/)