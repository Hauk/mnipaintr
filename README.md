# mnipaintr - A miniature painting support application

mnipaintr is an application aimed at miniature painters and tabletop war gamers. The idea of this app is to allow users to organise their painting backlog. Users can enter in the miniatures they have in their collection into their own personal library, which will keep track of the status of the miniature e.g. they can assign the miniature a status(such as new in box, unassembled, basecoated, complete, etc) depending on its current state.

I'm building this app for myself because it will help me kill two birds with one stone; I need to practice my Java and JavaScript and I need to keep track of my miniatures painting progress.

As a miniature painter I naturally have a completely chaotic miniature collection and I have boxes and boxes of unassembled and half finished miniatures that I need to organise. I was originally using Google Sheets to keep track of them, but I believe this problem will allow me to make something that anyone can use.

## Architecture.

I'm looking to build the entire front end in Ember JS, and have it query a JAVA rest API such as Jax-RS, all deployed to production through Tomcat.

## A warning!

Initially this app will be quite primitive, as it is my first foray into building a full application. The milestones will be incredibly tiny, but with the hope that incremental achievements will yield results that can build on top of each other. i.e. Don't expect miracles. There will be mistakes.

### First steps.
The very first step will be to sit down and map out with a pen and a paper what the basic Milestone 0.1 UI is going to look like.

There will be a form that will allow a user to enter in details of a miniature, and when they save it, the data will be persisted to the database.
There will be a query form that will allow users to query for all the miniatures in their collection which will then be rendered.

I said primitive and I mean it. :) Carts and horses and all that.
