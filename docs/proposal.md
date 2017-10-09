# Nau Proposal

Given the absence of Google Shopping as a mobile application, we’ve decided to create a functionally similar mobile application called Nau that will serve as both an availability check and price comparator for products of the user’s choosing in their vicinity.

<br>

Nau allows for users to enter a product name and a search radius. Upon querying all the nearby retailer's inventories based on the search inputs, it will display either in list view or map view the product and store information.

## MVP List

This app will, at a minimum, satisfy the following criteria with smooth, bug-free navigation:

- New user signup and signin + authentication
- Demo website showcasing relevant app features
- User search for a product of interest
- Display of the stores/products that satisfy the search criteria
- Implementing Google Map’s API
- Production README

## Technologies & Challenges

Technologies we are planning to use are the following:
* FrontEnd:
  - ReactJS
  - HTML5
  - CSS3

* BackEnd:
  - Express.js
  - MongoDB(Nosql Database)

<br>
The technical challenges for the application will be:
* Connecting our front-end with mongoDB, i.e. our back-end database
* Correct API calls and understand how to handle the CORS Http requests
* Creating a User interactive and pleasing UI for good user experience

## Group Members & Work Breakdown

1) Justin Shieh
* Working on writing and handling a professional proposal for the app
* Timeline manager
* Co-lead for implementing user Auth via CORS Http requests
* Researching new technologies and appropriate libraries to incorporate into the project
* Working on implementing the frontend using ReactJS

2) Priya Mangal
* Working with Justin on writing the proposal technologies
* Co-lead for implementing live-map functionality
* Working with Rachel on the backend to seed the data to our app

3) Rachel Jacobson
* Designing the wireframes for the mobile app
* Co-lead for implementing backend using mongoDB and Express.js
* Working on writing scripts to fetch data using Goodzer API
* Writing the production README for Nau to make it easy to understand the overall functionality of the app

## Implementation Timeline

1) Monday:
* Implementing User Auth for the app to enable user login/signup feature
* Working on creating API on Goodzer to fetch inventory data from grocery stores
* Working on Splash Page design and appealing styling

2) Tuesday:
* Working on creating appropriate Product database using MongoDB
* Seeding Product data to the database in a Nosql format basically key-value pairs
* Accessing the database using logic written in express.js with Javascript

3) Wednesday:
* Creating a frontend for products index page
* Displaying 10 products for all stores in a page
* Auto load more products at the end of the page

4) Thursday:
* Creating a product show page to display product information
* Start adding google maps on the app index and show to display store location
* Implementing product show page to display product with map pin

5) Friday:
* Continuing on google maps
* Sort with price, distance etc

6) Weekend:
* Style and pretty up our different frontend pages and make sure the UX is smooth and nice
* Filter search - filter by brand, location, map etc (bonus if time permits)

<p>Bonus</p>
Deploy on Play store

## Wireframes
1) Auth page

2) Search page
 * Product input
 * Location input
 * Search radius
 * Whether you need it now (aka only show stores open now)

3) Index page - List view
 * Store name
 * Product availability and price
 * Distance from set location
 * Maybe store hours still?

4) Index page - map view
 * Just show the store name and price

5) Show page
 * Product information/price
 * Store information (business hours and phone number)
 * Ability to save it to a “favorites” list - BONUS

6) Favorites - BONUS

```
NOTES: potential solution/fix to our concern for getting too much data back from queries:
Have all the results from the same store in another show page
</p>
```
