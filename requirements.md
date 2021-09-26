# Prep 4

## User Stories

1. As a user, I want to see art portraits from different museums all over the world.
2. As a user, I want to see art works from artists all over the world.
3. As a user, I want to add the objects I like to my feed.
4. As an artist, I want to be able to share, edit, and delete my art works.
5. As an artist, I want to receive feedback from users.

## Vision

Throughout the past couple of years and due to covid-19, people couldn’t attend art galleries/museums , and artists were unable to share their work and show it to the world.
So we decided to design an app that gathers artists and art lovers, the application will maily provide the following features:  

1. Allow artists to share their work and contact information in case anyone was interested. 
2. Allow people to view artworks from various mesuems and artists.

We aim to become the largest art-lovers social media platform over the world :)

## Scope 

### In:

1. The web app will provide users with art works from 3 different museums along with information about each peace.
2. The web app will allow users to have 2 types of accounts: a normal user/viewer account and an artists account.
3. Users will be able to Like, Share, and Comment on their favorite art works.
4. Artists will be able to share their work on their feed and on the app's homepage.

### Out:

Our product is not an e-commerce website, so users and artists will not be able to buy/sell works throughout it.

## Stretch goals 

Creating an algorithm that suggests places/events for the user based of their feed

## Functional Requirements

A visitor can view objects on the homepage.
A visitor can create an account and have a feed.
A user can add objects to their feed.
A user can like/comment on objects.
An artists can add, edit, delete objects.
An artists can like objects posted by others.

## Non-Functional Requirements

1. User-friendly app.
2. Secure log-in using auth0.

## Domain Modeling 

Domain Modeling is a way to describe and model real world entities and the relationships between them, which collectively describe the problem domain space.
Derived from an understanding of system-level requirements, identifying domain entities and their relationships provides an effective basis for understanding and helps
practitioners design systems for maintainability, testability, and incremental development. Because there is often a gap between understanding the problem domain and the
interpretation of requirements, domain modeling is a primary modeling area in Agile development at scale. Driven in part from object-oriented design approaches, domain
modeling envisions the solution as a set of domain objects that collaborate to fulfill system-level scenarios. In SAFe, domain modeling connects to backlog items at the
Team, Program, Large Solution and Portfolio levels and provides a common language for the entire organization. Especially important is its connection with the Nonfunctional
Requirements (NFRs) that may affect certain areas where “alternative design approaches” are sometimes used to satisfy the corresponding NFRs. Domain modeling also provides
the Agile organization with opportunities for use of Agile-friendly design patterns and approaches that enhance velocity over the long term. As the system design changes,
refactoring and updating the domain model is vital to maintaining a continuing understanding of the system, and goes hand in hand with code refactoring to help control the
inherent complexity of software systems.

## Database

Allmusemesmodal : contain all the art photos ex: any art from the gallery page will be here .
Usermodal: contain the user login data ex: any data in the user feed page will be here  .
Artmodal : contain the artist data ex: any data in the user feed page will be here.

### Does a single item in your database “belong to” just one other item in your database?
 - We use a art model and its have the image of the art and the artist name and date
 - 
### Does a item in your database “belong to” multiple other items in your database?
 - we use a user model and its have user name and user email and liked item and the user can have multiple liked items
 - 
### Do many items in your database relate to many other items in your database? 
- we have multiple museums and each musem have multiple items
