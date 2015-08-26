# Drupal 7 Boilerplate 
A generic Drupal 7 website with a full scaled cms, admin & frontend theme.
Structured with slick clean page manager menu rewrite and ctools panels.
Responsive theme

# Tech Kit
MySQL <br />
PHP, Drupal 7<br />
Jquery <br />

# Description
This is a simple template for a generic invitation page with an email input text. 
An invitation mail will be sent to a user along with a confirmation link and a viral link to recommend the
product to other friends through social media widgets (Facebook & Twitter).
All data is stored in mongoDb with a simple friendly admin interface.


# Snapshots

### Frontpage

http://invitationpage.url

![alt tag](https://raw.github.com/daniel-costa-hk/invitationpage/master/public/images/snapshots/invitepage_frontpage.png)


### Admin

http://invitationpage.url/registrations

![alt tag](https://raw.github.com/daniel-costa-hk/invitationpage/master/public/images/snapshots/invitepage_admin.png)


# Motivation
An example of integrating traditional marketing viral pages with new techkits.

# Installation

### Mac & Linux

Install [Node.JS](https://nodejs.org/) <br />
Install [Mongo.DB](https://www.mongodb.org/)
* (sudo) mongod 
* (sudo) node bin/preinstall.js
* (sudo) npm install -g nodemon
* nodemon app.js
* navigate to localhost:3000  (listening on port 3000 by default)

> You’re running! (If any issues, check the console for any errors.)

> The application will create a user collection on Mongo DB. <br />
> Configure the settings in lib/config/development.json & lib/config/production.json <br />
> Setup the email account router to send the email (Google mail by default) <br />
>> Note: If you use your own account for testing purposes please read:
>> https://support.google.com/accounts/answer/6010255?hl=en

### Windows
Not really sure :_)

# License

GNU General Public License


