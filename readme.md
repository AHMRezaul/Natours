<h1 align="center">
<img src="https://github.com/AHMRezaul/Natours/blob/main/images/logo-green-round.png"  width="200" height="200" />
<br> Natours </br>
</h1>

<h4 align="center">
A website for booking tours built using Node JS

Website URL: https://natours-ahmrezaul.herokuapp.com/ 
</h4>





## Overview

Natours is a website for tourists and enthusiastic travellers who love to explore the nature as well as enjoy a beautiful and relaxing vacation.
The website offers the users a chance to checkout the tourist spots available at that time of the year, what routes to take, get a guide, read reviews of the guided-tours and finally book the tour for themselves to enjoy.
It's simple to signup and login to your account. You can update your profile, read and provide reviews of tours, rate tours and check out facts about the location of the tours. You can also check the map integrated into the website to view the route that would be taken. And finally, you can book the tour with just a simple card transaction that is 100% secure. 

## Website details

* *Login* using an existing account or create an account using *Signup*.
* You can visit the homepage without logging in. The tour details can also be viewed without logging in.
* In order to book a tour, provide review or rating, you need to signup with a new account or log into you existing account.
* You can edit your username, profile photo and password any time from the *Profile* section, clicking on the avatar on the upper right corner after logging into you account.
* You can view any tours you have already booked in the *manage my booking* section on your profile.
* In order to book a tour, go to the *details* section of the tour, scroll down and select *Book the tour*. This will redirect you to a secure gateway for card transaction. All card transsactions are 100% secure and no information is stored.
* The tour detail section contains the details, facts, reviews, rating and information about the tour. A map will show you the location of the tour in realtime.

## Technical Overview

The website is built using the following technologies:

  1. Node JS
  2. Express
  3. MongoDB
  4. Pug
  5. Mapbox
  6. Heroku
  
The website was built using node js and express. For database, MongoDB was used to store the user data, tour data and reviews. Pug was used to create the frontend part. Heroku was finally used to launch the website to the cloud.

### Tools used

* [NodeJS](https://nodejs.org/en/) - JS runtime environment
* [Express](http://expressjs.com/) - The web framework used
* [Mongoose](https://mongoosejs.com/) - Object Data Modelling (ODM) library
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Cloud database service
* [Pug](https://pugjs.org/api/getting-started.html) - High performance template engine
* [JSON Web Token](https://jwt.io/) - Security token
* [ParcelJS](https://parceljs.org/) - Blazing fast, zero configuration web application bundler
* [Stripe](https://stripe.com/) - Online payment API
* [Postman](https://www.getpostman.com/) - API testing
* [Mailtrap](https://mailtrap.io/) & [Sendgrid](https://sendgrid.com/) - Email delivery platform
* [Heroku](https://www.heroku.com/) - Cloud platform

### Details

* The backend of the website was completely built on ***Node JS*** and ***Express***. 
* For database, ***MongoDB*** was used. The database was linked using a secret password and key. The database contains all the information regarding the tours, reviews and the users. The user password is encrypted and stored with much security. The password cannot be retrieved by anyone, even the admin, after it has been encrypted and stored. The user can however change the password from the account settings. In case the user forgets the password, the user can request to reset the password which has also been implemented. The password reset link would directly be sent to the user's email address. The user can choose to provide a profile picture if they wish.
* The frontend of the website was designed using ***Pug***.
* For booking transaction, ***Stripe*** was used. Stripe is a secure online transaction gateway that is used by many well known applications. For now, test mode is activated.
* For the development stage, ***Postman Application*** was used for debugging purposes.
* ***Mapbox*** was used to render and load a realtime map with the location of the tours.

### Installation

Download all the files from the github and open ***VS Code***.
Open the **Terminal** and install all the dependencies one by one mentioned in the *package.json* file.
Example:

```
npm i filename@version
```
For dev dependencies, use the following format:

```
npm i filename@version --save-dev
```

For uninstalling any dependencies use the following format:

```
npm uninstall filename@version
```
After all the dependencies are installed successfully, a new folder called *node_modules* will be created.
Edit the *config_env* file in oder to run the website successfully. Each value is to be provided from your own account.
Provide MongoDB connection links, password etc., SendMailer account, Stripe secret key and webhooks etc.

Now, in order to run the website, the server needs to be started. The following code will enable you to start the server and host the website locally.
```
nodemon server.js
```
The server will automatically restart when any file is changed and saved.
To view the website, go to the web browser and visit the following path:
> 127.0.0.1:8000/

You can signup using any demo email accounts. For pre existing accounts, use the following username and password:
> user@example.com

> test1234

Use the following demo card number to book tours:
```
  - Card No. : 4242 4242 4242 4242
  - Expiry date: 02 / 22
  - CVV: 222
```

## Screenshots

### Home Page
![](https://github.com/AHMRezaul/Natours/blob/main/images/home1.png)
![](https://github.com/AHMRezaul/Natours/blob/main/images/home2.png)

### Tour Details
![](https://github.com/AHMRezaul/Natours/blob/main/images/tour-details1.png)
![](https://github.com/AHMRezaul/Natours/blob/main/images/tour-details2.png)
![](https://github.com/AHMRezaul/Natours/blob/main/images/tour-details3.png)
![](https://github.com/AHMRezaul/Natours/blob/main/images/tour-details4.png)
![](https://github.com/AHMRezaul/Natours/blob/main/images/tour-details5.png)

### User Account
![](https://github.com/AHMRezaul/Natours/blob/main/images/account1.png)
![](https://github.com/AHMRezaul/Natours/blob/main/images/account2.png)

### Card Transaction using Stripe
![](https://github.com/AHMRezaul/Natours/blob/main/images/stripe.png)

### Login
![](https://github.com/AHMRezaul/Natours/blob/main/images/login.png)

### Signup
![](https://github.com/AHMRezaul/Natours/blob/main/images/signup.png)



***Heroku does not allow the server to run a long time, so the website may not always be live.*
