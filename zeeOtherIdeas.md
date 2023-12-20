
# Project Title

creativityHub

## Overview

Connect and collect. map the best pop up event and performances, promote your art and keep your favorites.

### Problem

Connoisseurs, ceators and venues all benifit eachother in different ways,
but don't have a centralized place to interact.

### User Profile

People who create and perfrom.
People who enjoy art and performances.
Venues who want to draw people in and host.

### Features

User Profiles
  -  sign up as a connoisseur to peruse world wide art and local events
  -  sign up as an creator and get eyes on your work and ears for your music
  -  sign up as a venue to host pop up gallery events and get people in your place

Shoppingcart / marketplace - patrons to artists
scheduling calender / map -  artists to venues
collaboration chat - artist to artist

New Art feed

Art Data Base

Event Data Base 

Chat history Data Base

A map to render events on.

## Implementation

### Tech Stack

React, Node, Express, MySQL

### APIs

PayPal

Leaflet

### Sitemap

(1) Sign up page: one of three profle styles: creator, connoisseur or venue

(2) Profile page: connoisseur Profile view / edit

                  creator Profile view / edit

                  venue Profile view / edit

(3) Feed : new audio / visual / textual creations

(4) Marketplace page : connoisseur - artist purchase or donate

(5) Scheduleing page : creator - venue plan events

(6) Map : show current and upcoming event and live collab locations

(7) Collab chat : public creator - creator chat


### Data

Creation Data Base
  - visual
  - textual
  - audible 

Event Data Base 
  - addess
  - lat
  - long 
  - time

Chat history Data Base
  - post

Profiles
   - auths
   - type
   - user info


### Endpoints

/feed
  .get(_req, feed of 10 most recent creations)
  .post(creation, res)

/map
  .get(_req, event location info info)

/profile/:id
  .get(_req, )

/profile/:id/schedule
  .get
  .post

/market/:id                 // view single creation from feed
  .get(_req, chat and creation)
  .post(make bids)

/market/:id/purchase

/signup
  .post

/login
  .post

/colabchat
  .get
  .post
code cr 
### Auth

JWT

## Roadmap



## Nice-to-haves

three more weeks to work on it





### Other Ideas ###


##### one ##########################################################


.breifcase

go deeper than the headlines and get up to speed with this headline history enhancer. 

why: headlines and articles by their nature are focused on current situations, 
  but nothing exists in a vaccum and it import understand to know the history that leads to current events. 
  Having a summary of the histroy based aroung the current headline is faster than researching other headlines.

who: can be geared to specific industries. articles that are import to them and historical context relevant to their industry

pros: cool animation 
      mulitple apis

challenges: news and llm apis do not provide satisfactory content


##### two ##########################################################


lockdown

a dynamic multiplayer memory card game.

why: it's a great game I love to play and people like to learn to play

who: people who like card games but don't like to shuffle

challenges: making the server robust enough to hand multiple clients
            learning a card game might be too difficult for the people watching
