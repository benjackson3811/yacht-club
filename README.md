<a name="top"></a>

# Milestone project 5 Frontend

--- 

This project has its own backend API. The link to this repository is [](). 

Live Website

View Live Wesbite here: ####

---

### Am i response image

--- 


### Project purpose and description

Yacht Club is a website for a fictional yatch club based in the UK. 

[Wikipedia](https://www.wikipedia.org/) defines the purpose of a "yacht club is to celebrate boaters and the sport of yacht racing, sailing, and cruising. What Is A Yacht Club? A yacht club is a social membership sports club for boaters."

The Yacht Club website has been created as 5th Portfolio project for the Code Institutes fullstack developer program. 

The website goal is to allow users to view and share pictures of trips taken and future trips with the Yatch club.  

The website is designed as a browser-based interface to enable;
- users to create, read, comment and vote on shared content.
- content to be searched and catergorised.
- search results can be filtered on username, popularity, date created, title, content keywords and category. 

The project is built using React, JSX, (HTML, Javascript and CSS), specific frameworks and libraries (detailed in a below section) and connected to a separate backend API (also built for this course).

[Back to top](#table-of-content)
---

### Site owner's goal

My family are keen sailers and belong to sailing club that allows them to sail with friends all around the UK and Northern Europe. At the minute the only place they can share their pictures is Facebook. I wanted to create a place where they could share their pictures, memories and feedback on old trips.

[Back to top](#table-of-content)
---
### Site User's goal

- To create a website for club members to share their trip pictures to club members. 
- To allow the club to show pictures of the previous adventures the members have been on. 

[Back to top](#table-of-content)
---
### User Stories

The below user stories have been defined for the project.

#### Navigation 
- [] Navigation: As a user I can view a navbar from every page so that I can navigate easily between pages.
- [] Routing: As a user I can navigate through pages quickly so that I can view content seamlessly without page refresh

#### Authentication and account creation
- [] Authentication - Sign up: As a user I can create a new account so that I can access all the features for signed up users.
- [] Authentication - Sign in: As a user I can sign in to the app so that I can access functionality for logged in users.
- [] Authentication - Logged in Status: As a user I can tell if I am logged in or not so that I can log in if I need to.
- [] Authentication - Refreshing access tokens: As a user I can maintain my logged-in status until I choose to log out.
- [] Avatar: As a user I can view user's avatars so that I can easily identify other website users.
- [] Navigation: Conditional rendering - As a logged out user I can see sign in and sign up options so that I can sign in/sign up.


#### Trips
- [] Create Trips: As a user I can create a Trip / post so that I can share my images of a recent Yacht club trip!
- [] View a Trip: As a user I can view the details of a single trip picture so that I can learn more about it.
- [] Like a Trip: As a  user I can like a shared trip so that I can show my support for the trip that interest me.
- [] Edit a Trip: As a users, i can edit a trip/ post title and description if i need to update a detail.
- [] Delete a Trip: As a user I can delete a Trip / post so that no one can view the picture.
- [] Search: As a user, I can search for specific trips/ users/ keywords, so that I can find specific details/ trips / user profiles I am most interested in.
- [] Trip date: As a user I can see how long ago a Trip was made so that I know when the trip was completed.

#### The Trips Page
- [] View most recent Trips: As a user I can view all the most recent Trips, the most recently created shown first so that I am up to date with the newest content.
- [] Liked trips: As a logged in user I can view the trips I liked so that I can find the trips I enjoy the most
- [] Followed users: As a logged in user I can view content filtered by users I follow so that I can keep up to date with content.
- [] Infinite scroll: As a user I can keep scrolling through the images on the site, that are loaded for me automatically so that I don't have to click on "next page" etc


#### Comments
- [] Trip page: As a user I can view the trips/ posts page so that I can read the comments about the trip.
- [] Create a comment: As a logged in user I can add comments to a post so that I can share my thoughts about the trip.
- [] Comment date: As a user I can see how long ago a comment was made so that I know how old a comment is.
- [] View comments: As a user I can read comments on trips/ posts so that I can read what other users think about the trips/ posts.
- [] Delete comments: As an owner of a comment I can delete my comment so that I can control removal of my comment from the application
- [] Edit a comment: As an owner of a comment I can edit my comment so that I can fix or update my existing comment

#### The Profile Page
- [] Profile page: As a user I can view other users profiles so that I can see their posts and learn more about them
- [] Most followed profiles: As a user I can see a list of the most followed profiles so that I can see which profiles are popular
- [] User profile - user stats: As a user I can view statistics about a specific user: bio, number of posts, follows and users followed so that I can learn more about them
- [] Follow/Unfollow a user: As a logged in user I can follow and unfollow other users so that I can see and remove posts by specific users in my posts feed
- [] View all trips created by a specific user: As a user I can view all the trips created by a specific user so that I can catch up on their created trips, or decide I want to follow them
- [] Edit profile: As a logged in user I can edit my profile so that I can change my profile picture and bio
- [] Update username and password: As a logged in user I can update my username and password so that I can change my display name and keep my profile secure

[Back to top](#table-of-content)
---

### Structure

#### Wireframes

##### HomePage
![Screenshot](/src/images/readme-images/home-page.png)

##### Profile Page
![Screenshot](/src/images/readme-images/profile-page.png)

##### Sign In
![Screenshot](/src/images/readme-images/sign-in.png)

##### Sign Up
![Screenshot](/src/images/readme-images/sign-up.png)

##### Trip Detail
![Screenshot](/src/images/readme-images/trip-detail.png)

[Back to top](#table-of-content)
---

#### Database Schema

![Screenshot](/src/images/readme-images/database-schema.png)

[Back to top](#table-of-content)
---

### Design Choices


#### Colour Scheme

The colour scheme chosen for the website is light colours with stong links to summer and sailing. They provide strong contrasts which will make the information clear and easy to read for the user.
![Screenshot](/src/images/readme-images/palette.png)

[Back to top](#table-of-content)
---
#### Fonts and Typography

- Ruda font used on site, fall back font is sans-serif. Example of Ruda font from.
![Screenshot](/src/images/readme-images/ruda_font.png)


[Back to top](#table-of-content)

---
### Features

- Navbar
- Sign up
- Sign in
- Feed
- Add Trip
- Trip Detail
- Edit trip
- Delete Trip
- Profile
- Follow/ Followed
- Comments
- Categories
- Footer
- Future Features

[Back to top](#table-of-content)
---

### Technologies Used

### Languages

- HTML / JSX (JavaScript XML)

- CSS

- Python

- Javascript

[Back to top](#table-of-content)
---
### Frameworks

- Django: A high-level Python web framework used for building the Yacht Club API.

- React: A JavaScript library for building user interfaces. It is commonly used for creating dynamic and interactive components in web applications.

- Cloudinary: A cloud-based media management platform used for storing and serving images in the Yacht Club project.

[Back to top](#table-of-content)
---

### Database

- ElephantSQL: ElephantSQL is a PostgreSQL database as a service. It is used as the database for the Yacht Club project, providing a reliable and scalable storage solution for the application's data.

[Back to top](#table-of-content)
---

### Tools

- Git: A distributed version control system tracking project source code changes.

- GitHub: A web-based hosting service for version control repositories for storing and managing the project's source code.

- Gitpod: An online integrated development environment (IDE) used for developing and testing the Yacht Club project.

- Heroku: A cloud platform that enables deployment and hosting of web applications. Heroku was used for deploying the Yacht Club project to a live server.

- Balsamiq: A wireframing tool for creating mockups and prototypes of the Yacht Club website.

- DrawSQL:https://drawsql.app/

- Google Fonts: An open-source fonts used for typography on the Yacht Club website.

- Font Awesome: A library of free  icons to the Yacht Club website.

[Back to top](#table-of-content)
---

### Methodology

#### Agile Project Management

[Back to top](#table-of-content)
---

### Bug Tracking
[Back to top](#table-of-content)
---

### Documentaion
[Back to top](#table-of-content)
---
### Testing

Validator
w3c
js bin
ci linter - python
[Back to top](#table-of-content)
---

### Deployment
[Back to top](#table-of-content)
---

### Credits

- [Wikipedia] (https://www.wikipedia.org/) - used for the description of a yacht club.

[Back to top](#table-of-content)