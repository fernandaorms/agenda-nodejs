# Agenda Project

#### Welcome! [You can check live project here.](https://agenda-nodejs-1kdf.onrender.com/))

This a simple project of an **Agenda** where the goal was having a **CRUD** of contacts. 
After creating an account, the User can Login and access his contacts lists, being able to Create, Update and Delete a Contact.

This project comes from a Javascript course (you can check the details at [js-course repo](https://github.com/fernandaorms/js-course/tree/main)), but over there we only had a single contact list that was managed by all Users. So I decided to make some improvements and modifications, like:

 1. Update the Contacts Schema and the logical to have the contacts associated to a User, so each User has his unique contact list
 2. Create an Account Management page where the User can edit his account's details
 3. Separe the Login and Register in different views and routes, instead of having it all together in a single page
 4. Add frontend validation to the forms, so it's not necessary to make a request to the server every submit to making simple validations
 5. Remove from anonymous views some buttons and links that should be only available once the user is logged in