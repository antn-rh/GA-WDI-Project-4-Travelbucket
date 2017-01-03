# Travelbucket

### Links to App
[Link to Github Frontend](https://github.com/antoniolrhee/travelbucket_frontend)

[Link to Github Backend](https://github.com/antoniolrhee/travelbucket_api)

#

[Link to Deployed Frontend](https://antoniolrhee.github.io/travelbucket_frontend/)

[Link to Deployed Backend](https://travelbucket-api.herokuapp.com/)

### About the project 

Travelbucket is a single-page application designed for organizing trips! It is a way to build your itineraries from the ground up using APIs like Google Calendar, Google Maps, and Yelp. Whether it's flight and lodging information, landmarks, attractions, restaurants, or notes about your travel destination, users can store them all in their Travelbuckets.

### Installation Instructions

Use the deployed links above OR: 

1. Visit the Github links for the frontend and backend and click 'Clone or Download'
2. Copy the provided links and paste them individually into the terminal followed by 'git clone' each time
3. At the root of the api directory in your terminal, run mongod in one tab and nodemon in another. Visit localhost:3000 to see the API documentation page.
4. At the root of the frontend directory in your terminal, run http-server. Visit localhost:8080 to see the landing page of the app.

### MVP 

The minimum viable product is a single-page application that uses web token based authentication and allows users to create, read, update, and delete trips. Users should be able to store transit information and other important notes as they create a trip. Another goal is to incorporate Google Calendar and Google Maps to add more organizational features to the trip planning functionality. 

### Technologies Used

1. HTML5
2. CSS3
3. MEAN Stack (MongoDB, Express, AngularJS, Node.js) 
4. Angular Material (styling)
5. Google Maps API
6. Google Calendar API
7. Yelp API 
8. Postman (testing)
9. JSON Web Tokens (token-based authentication)
10. Satellizer (token-based OAuth)

### Approach

My approach to building this project was taking it one model at a time. Within the models, I divided my work into backend work and frontend work. I started by creating the user model and setting up the necessary backend routes. I brought in JSON Web Tokens as well as Satellizer to get authentication working. After my backend was set up, I used Postman to test that my backend was working properly and moved onto doing user model frontend work. I made views and forms for signing in and once I got users to be able appropriately sign in and out I focused my attention on the trip model. Again, I coded the backend first and tested it on Postman, then worked on views and forms in the frontend. AFter getting full CRUD on my trip model, I began to incorporate Google Maps API as well as the Yelp API to get a map and search function going. Finally, I added styling to my application using Angular Material. 

### Trello Board

[Link to Trello](https://trello.com/b/1akP2dSE/project-3-Travelbucket)

### Wireframes & ERD

![](http://imgur.com/kGCkLdI.png)
![](http://imgur.com/hteXyOX.png)
![](http://imgur.com/9Xe1u00.png)
![](http://imgur.com/VKe5xEG.png)
![](http://imgur.com/OZ0m3K8.png)

### Unsolved Issues

- Issue where the username in the navbar does not refresh quickly enough
- The search function needs some tweaking; there are random results for specific search queries
- There is an issue where the app breaks when certain form fields are left blank
- The ng-click that calls addToBookmarks() does not work 
