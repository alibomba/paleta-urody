# Paleta Urody
Paleta Urody is an imaginary beauty salon website. Frontend is built in React, Typescript and CSS Modules with integration of the REST API built in Laravel. Communication between frontend and backend is implemented with Axios library. Frontend routing is made with react-router-dom. The client can book the date of an appointment along with the info if a given date is already taken or not. There are blog posts listed from the database and you can send a message to the support via contact form on the website. Messages from clients are automatically sent to the admin e-mail address which can be specified in a CMS (Content Management System) after logging into it. Besides the admin panel enables browsing all the booked appointments or adding, editing and deleting blog posts. Moreover after booking the appointment the user is receiving an e-mail with its date and if the user is browsing the site and the blog post is published at that time, a realtime notification is sent to the user via WebSockets protocol.