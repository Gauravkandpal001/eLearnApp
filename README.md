# eLearnApp
An eLearn app to bring learners and educators on single platform

    kickstart Frontend Framework
    MongoDB
    Handlebars Templating
    Async

<br/>

001 App  Kickstart Setup Part A

    $ express
    $ npm install
    $ npm install --save bcryptjs
    $ npm install --save passport  
    $ npm install --save passport-http     
    $ npm install --save passport-local
    $ npm install --save mongodb
    $ npm install --save mongoose
    $ npm install --save handlebars    
    $ npm install --save express-session
    $ npm install --save express-messages
    $ npm install --save express-handlebars
    $ npm install --save connect-flash
    $ npm install --save express-validator

<br/>  

    $ mongo
    $ use elearn
    $ db.createCollection('users');
    $ db.createCollection('students');
    $ db.createCollection('instructors');
    $ db.createCollection('classes');
    $ show collections


002 App Kickstart Setup Part B

    $ npm start
    localhost:3000

http://www.99lime.com/elements/


003 Fetching Classes - Basics Part A

    $ mongo
    $ use elearn
    $ db.classes.insert({title:'HTML 101', description:'Description 1', instructor:'Brad Traversy'});
    $ db.classes.insert({title:'Intro to PHP', description:'Description 2', instructor:'John Doe'});

004 Fetching Classes - Basics Part B

    $ npm start

005 Fetching Classes - Final Features

    $ npm start

006 Registration Login - Basics Part A

    $ npm start

007 Registration Login - Basics Part B

    $ npm install --save async

008 Registration  Login - Final Features

    $ npm start

009 Student Class Registrations

    $ npm start

010 Instructor Access

    $ npm start

011 Class Lessons Part A

    $ npm start

012 Class Lessons Part B

    $ npm start
