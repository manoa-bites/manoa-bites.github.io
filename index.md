## Table of contents

* [Overview](#overview)
* [Team Contract](#team-contract)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Continuous Integration](#continuous-integration)
* [Team](#team)

<!--
   NOT HERE YET
* [Walkthrough Videos](#walkthrough-videos)
* [Example Enhancements](#example-enhancements)
-->

## Overview

Manoa Bites is a web application designed to help students and staff at the University of Hawaii at Manoa easily find food options across campus locations. With Manoa Bites, users can discover available menu items, search for specific restraurants, and find out which dishes are being served on any given day. Key features include:

* **Campus-wide Food Directory**: Consolidates food options from Campus Center, food trucks, Manoa Gardens, and other campus locations.
* **Real-time Updates**: Vendors can log in to update daily menus, ensuring users always see current options.
* **Personalized Experience**: Users can set food preferences and get suggestions tailored to their tastes.
* **Roles**: Three user roles (Users, Vendors, and Admins) for personalized and manageable access.


## Team Contract
Our team contract can be found <a href="https://docs.google.com/document/d/1nAwAa54P1vTGNB8MZJTzEddC39ePGWRlMXVhibOSc9M/edit?tab=t.0">here.</a>


## Deployment

Manoa Bites is deployed on <a href="https://manoa-bites.vercel.app/">https://manoa-bites.vercel.app/</a> for easy access by the UH Manoa community. To start using the app, go to the deployment link and create an account or log in to access all features.

## User Guide 

This section provides a walkthrough of the Manoa Bites user interface and its capabilities.

### Landing Page/Directory

<img width="100%" src="assets/landingpage.png" alt="Current Landing Page">

The landing page of Manoa Bites brings up this page where they are already presented with cards displaying restaurants and their restaurants. We are currently in the middle of testing the functions to add/edit restaurants so our images are not fully uploaded yet. We also added a search bar that has zero functionality yet that we hope to get finished in M3.


### Map Page

<img width="100%" src="assets/mappage.png" alt="Current Map Page">

The Map index page is available to preview without having to log-in and displays an interactive Map centered at UH Manoa's Campus. There are markers here that make the locations easy to find.

### Sign in and Sign up

Clicking on the "Login" button on the right side of the nav-bar will pop up a dropdown menu that gives users the choice of signing in to an existing account or to sign up for a new account. Clicking on the Sign in, will navigate you to this page:

<img width="100%" src="assets/signin.png" alt="Current SignIn Page">

Clicking "Sign Up" will take you to this page:

<img width="100%" src="assets/signup.png" alt="Current Sign Up Page">

### Favorites Page

After Signing in to an existing account, users can access their favorite restaurants they saved but clicking on their email in the right of the navbar.

<img width="100%" src="assets/favoritestab.png" alt="Where favorite restaurants can be found">

Clicking on "Favorites" will take you to this page that loads the Restaurant cards you have saved.

<img width="100%" src="assets/favoritespage.png" alt="Current Map Page">

### FAQ

In the footer of our app, we have a few Links. The first link is our FAQ page:

<img width="100%" src="assets/FAQpage.png" alt="Current FAQ Page">

### Report a Problem

Another link we have is for reporting problems. This form allows us to receieve feedback from users that will be sent to the admin to review.

<img width="100%" src="assets/reportissueform.png" alt="Current Report Issue Form">

This form features a dropdown selection for topics that will allow for easier sorting when viewing the feedback as an admin.

<img width="100%" src="assets/issueformdropdown.png" alt="Current Issue Form Topics">

### Admin Page

When logged into the admin account, there is an option in the dropdown menu after clicking on your email.

<img width="100%" src="assets/admindropdown.png" alt="How to access admin information">

Clicking on Admin will take you to this page where the Admin can easily view current Restaurants, Locations, User, and Reported Issues

<img width="100%" src="assets/adminpage.png" alt="How to access admin information">

### Vendor Page

When logged in as a vendor, the same dropdown tab is available for Vendors but will only display their restaurant they add where they can edit, delete, or add a new restaurant.

<img width="100%" src="assets/vendorpage.png" alt="How to access vendor only information">

## Community Feedback

We welcome feedback to improve Manoa Bites! Please take a few minutes to fill out our [Manoa Bites Feedback Form]<a href="https://forms.gle/BzFbBFjH5P7m48dK6">(https://forms.gle/BzFbBFjH5P7m48dK6)</a>, which will help us enhance the user experience.

## Developer Guide

This section provides setup and development information for those who wish to contribute to Manoa Bites.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ManoaBites/Manoa-bites-app.git

2. Install the dependencies:
   ```bash
   npm install
   
3. Start the application:
   ```bash
   npm start
  


## Development History

### Milestone #1: Rough drafts

<a href="https://github.com/orgs/manoa-bites/projects/2">Here is the link to our M1 project page.</a>

For this Milestone, we primarily focused on setting up simple database models and pages/components. We have completed implementing the majority of our pages.

<img width="100%" src="assets/m1backlog.png" alt="M1 done">

### Milestone #2: Refinement

<a href="https://github.com/orgs/manoa-bites/projects/4">Here is the link to our M2 project page.</a>

In this upcoming Milestone we plan to add more information and functionality to our page. With our restaurant cards we aim to add more information about the restaurant(i.e. an image/logo, hours of operations, and brief description). Also we still need to make the favorites button on the restaurant card functional where it will save it to the Users favorites. 

<img width="100%" src="assets/m2backlog.png" alt="M2 done">

### Milestone #3: Finishing Touches

<a href="https://github.com/orgs/manoa-bites/projects/6/views/1">Here is the link to our M3 project page.</a>

In this Milestone we hope to finalize our model database and add the remaining restaurants in our page. We will be refining other elements as well such as our google map and our search bar.

<img width="100%" src="assets/m3backlog.png" alt="M3 start">

## Continuous Integration

[![manoabites-application-template](https://github.com/manoa-bites/manoa-bites/actions/workflows/ci.yml/badge.svg)](https://github.com/manoa-bites/manoa-bites/actions/workflows/ci.yml)

Manoa Bites uses GitHub Actions for continuous integration, ensuring code quality and passing tests on every commit. You can see the results of all recent "workflows" at <a href="https://github.com/manoa-bites/manoa-bites/actions">https://github.com/manoa-bites/manoa-bites/actions</a>.

<!-- 



## Walkthrough Videos

* [Manoa Bites Overview (5 min)](https://www.youtube.com/samplelink)
* [Manoa Bites Feature Walkthrough (10 min)](https://www.youtube.com/samplelink)


## Example Enhancements

Enhancements that could further improve Manoa Bites include:

* Adding notifications for when favorite items are available.
* Allowing users to filter menus by dietary preferences (e.g., vegan, gluten-free).
* Enabling a feedback system for users to rate menu items.
--> 

## Team

Manoa Bites is designed, implemented, and maintained by:

- **John Bernardo** 
- **Leighton Miguel** 
- **Caleb Hopkins** 
- **Jingyu Huang** 
- **Pelita Felicitas** 


