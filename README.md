### Event List Site
Note: Look at [proposal.md](proposal.md) for the project proposal submission

# README
__Project link__: https://cs4241-final-project-zzsv.onrender.com

## Project Description
We created an Event Management web application. It is a platform designed to create an event, invite guests, and manage event and guest details. Users can register, invite guests, uninvite guests, and view the guest list for an event. Admins have an expanded set of abilities including being able to create events, manage guest lists, change event details, invite users to an event's list, and assign admin to users.

The purpose of this project was to create a website for a local WPI community to more efficently organize events for their members. The idea is for the community leaders to be the admins and manage the events, while the community members sign up to be users. These users can write the name of guests they choose to bring, whether they are part of the community or not. The user's password are protected and remembered in the database, however the admins would be able to view the user's name. 

## Instructions & Login Information
Login:
- Username: mmouse
- Password: !123

- Username: dduck
- Password: !123

Note: The "mmouse" account has more pages to view and addtional management features.

Follow the buttons to edit events/add guests/delete guests. 

## Outline of Technologies Used
- __React__: Used to make all page components 
- __Mongoose__: Made schemas and hold all user data
- __Framer__: Added animations to site
- __Passport__: Used for adding authentication for login
- __DaisyUI__: Used for styling components
- __Tailwind CSS__: Used this framework for styling
- __Node JS__: Used to host our API and provide data to our frontend from our MongoDB Atlas backend

## Challenges
One challenge we ran into was authenicating login for everyone on the team; sometimes there would be fetching issues while logging in even if no code has been changed. We also had difficulty deploying the project since we built the entire project before trying to host. Problems of any kind that arose were resolved by working together and communicating with each other so that multiple pairs of eyes were looking for bugs or issues. 

## Group Responsibilities
- __Alexander Beck__: backend - made database and created all necessary api calls, connected frontend and backend
- __Jayson Caissie__: frontend - used Framer motion to make the animations on the site, added search and scroll ability to tables, implemented user authorization.
- __Carlos Medina__: frontend - created table components and scroll capabilties, navbar, added tailwind and css for styling, format pages
- __Olivia Perez__: frontend - assisted with adding navigation, addGuest capabilities, guest list components, and readme
- __Jack Weinstein__: frontend - created project/start code, page navigation, page components, login and registration, format pages, connected frontend and backend

## Accessibility Features
- ![Lighthouse test](lighthouse.png)
- Made the lighthouse test 100 in Accessibility
