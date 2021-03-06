# Restaurant Reviews App

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

## Description

This simple application consists of 2 pages. First page allows a user to filter on a small list of restaurants based on location and cuisine type. If a user clicks the View Details link for a given restaurant, then the user is taken to the restaurant details page which consists of 
Restaurant name, hours, map and reviews.

## Starter Code

Starter code for this project provided by Udacity at: https://github.com/udacity/mws-restaurant-stage-1

## References

- Flexbox Tutorial: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- Service Workers: an Introduction: https://developers.google.com/web/fundamentals/primers/service-workers/

## How to start the Application

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

## CHANGELOG

### 2019-02-17

- Added lang attribute to html files
- Moved breadcrumb to nav section
- Added role to nav
- Added role="application" to maps
- Changed restaurant-name element to h2
- Changed attribute for restaurant image from name to alt
- Changed heading from h2 to h3 for Reviews section
- Fixed issue where Restaurant Name heading was hidden by nav when viewport width was too small
- Fixed horizontally scrolling issue