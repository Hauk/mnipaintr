# mnipaintr - A miniature painting support application

mnipaintr is an application aimed at miniature painters and tabletop war gamers. The idea of this app is to allow users to organise their painting backlog. Users can enter in the miniatures they have in their collection into their own personal library, which will keep track of the status of the miniature e.g. they can assign the miniature a status(such as new in box, unassembled, basecoated, complete, etc) depending on its current state.

I'm building this app for myself because it will help me kill two birds with one stone; I need to practice my Java and JavaScript and I need to keep track of my miniatures painting progress.

As a miniature painter I naturally have a completely chaotic miniature collection and I have boxes and boxes of unassembled and half finished miniatures that I need to organise. I was originally using Google Sheets to keep track of them, but I believe this problem will allow me to make something that anyone can use.

## Architecture.

I had originally planned to use Ember JS to handle all the framework for the front end, and had planned to have the Ember JS front end consume RESTful web services served up by JaxRS from a Java Spring MVC framework. I'm still going to keep the backend in Java and Spring as I want to get more familiar with these, but the front end will be built with AngularJS. I found Ember Data to be too restrictive in how it expects data to be served from the back end, so Angular will take some of the headache out of integrating the backend and the front end. I don't want to spend time hacking adapters together to get data to display. Clean code is the goal here.

## A warning!

Initially this app will be quite primitive, as it is my first foray into building a full application. The milestones will be incredibly tiny, but with the hope that incremental achievements will yield results that can build on top of each other. i.e. Don't expect miracles. There will be mistakes. I will be including milestones around the environment setup right up to what I think is required to break down the problem into manageable chunks.

### First steps.
The very first step will be to sit down and map out with a pen and a paper what the basic Milestone 0.1 UI is going to look like.

There will be a form that will allow a user to enter in details of a miniature, and when they save it, the data will be persisted to the database.
There will be a query form that will allow users to query for all the miniatures in their collection which will then be rendered.

I said primitive and I mean it. :) We won't be putting the cart before the horse here.
