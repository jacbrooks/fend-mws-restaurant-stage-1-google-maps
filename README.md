# Restaurant Reviews (Stage 1)

## Table of Contents

- [Overview](#overview)
- [Instructions](#instructions)
- [Where to Start](#where-to-start)
- [Code Requirements](#code-requirements)

## Overview

For the **Restaurant Reviews** project, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

## Instructions

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

## Where to Start

### Run it locally using Python HTTP Server:

1. Download as .zip file or clone this project:

   ```
   $ git clone https://github.com/jacbrooks/fend-mws-restaurant-stage-1-google-maps.git
   ```

2. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

3. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
4. Explore the provided code, and make start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
5. Write code to implement the updates to get this site on its way to being a mobile-ready website.

### Live Demo:

- Try it [here](https://jacbrooks.github.io/fend-mws-restaurant-stage-1-google-maps/)

## Code Requirements

- [Project Restaurant Reviews (Stage 1) - Starter Code](https://github.com/udacity/mws-restaurant-stage-1)
- [Normalize.css](https://necolas.github.io/normalize.css/)
