# Simple TODO App

Simple TODO app with Symfony(PHP) in RestAPI and ReactJS in front

API : with SYmfony(PHP) ( [SimpleTODOAppAPI] (https://github.com/dhmm/) )
Front : with React JS ( [SimpleTODOAppFront] (https://github.com/dhmm/) )

![Simple TODO App Screenshot](https://raw.githubusercontent.com/dhmm/SimpleTODOApp/master/sc.png)

### Repos...

It has 2 different repositories
1) API repo , 2) FRONT repo

### What you need ?
You must have installed the npm js
You must have installed 'symfony' executable for windows ( or other for Linux / MacOS )

### How to install

1) Download API repository
2) Enter in the API directory and then run
```
npm install
``` 
3) Then create a db named 'todo' in mysql
4) Then migrate the database from command line
```
php bin/console doctrine:migrations:migrate
```
5) Then run the symfony server with
```
symfony serve
```

6) Download the Front repository
7) Enter in the FRONT directory and then run
```
npm install
``` 
8) Run the front with
```
npm start
```
Thats is

### Question ?

You can ask me from 
Facebook : https://www.facebook.com/dhmmutlu
Linkedin : https://gr.linkedin.com/in/moutlou-nteli-chasan-moustafa-629a504a