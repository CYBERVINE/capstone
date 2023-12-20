
# Project Title

sonder

## Overview

Sonder is the sudden realization that every passer by is living a live as rich and deep as your own.

The world is the post and this is the comment section.

Map you thoughts and where you had them. Users get access to posts when they are get in proximity. 
they can then check your profile and view anything you have to promote.

### Problem

Places inspire thoughts that often go unshared.

"It's hard to walk a mile, but let's share a step"

### User Profile

Anyone who chuckles at or is moved by their own thoughts, and wonders about the minds of others. People who want to promote their minds and augment reality.

### Features

User Profiles

Comments Data Base

A map to render comments on.

The mobile location of users when they point

LLM content screening

## Implementation

### Tech Stack

React, Node, Express, MySQL

### APIs

ChatGPT

Leaflet

### Sitemap

Sign up

Personal Profile view / edit
  - defaults to anonymous avatar, but you can use your real info if you like
  - turn on wander mode to get notification when you are prominal to a post

Map page - comment pop up modal
  - Map you thoughts and where you had them. 
  - Users get access to posts when they are get in proximity. 
  - They can then check your profile and view anything you have to promote.


Other profiles ( only accessible when in promities with one of their mapped comments)
  - funnel people to you profile with you wit and insite
  - promote anything you want



### Data

NEED LOCATION DATA OF PEOPLE WHEN THEY POST (actual publishing can be delayed, but the comment must be mapped to when it was had)

Comments table with comment, location, time, and profile_id foreign key

Profile table with auth info name

### Endpoints

/comments
  .get( _req, comment info to mark on map )
  .post ( Lat Long Comment Time, res)

/comments/proximal
  .get ( current Lat Long, comments with similar Lat and Long are viewable)

/comments/:id
  .patch ( _req, likes)
  .delete (delete)

/profiles/:id
  .get (commentId, userProfile)
  .post (profile info, res)
  .patch (user auth, res)
  .delete (delete)

### Auth

JWT

## Roadmap

The only difficult I forsee is getting access to mobile phone location. 

Desktop is easy. Geolocation.getCurrentPosition(): Retrieves the device's current location.

Mobile has more protections that I havent had time to fully explore. 

Ngrock 

envyrock

audience comes last

## Nice-to-haves

  Wander mode to get real time notification when you are prominal to a post

  Add photo posts

  Add voice note






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
