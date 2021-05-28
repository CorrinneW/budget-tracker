# Budget Tracker PWA
Progressive web app using MongoDB and IndexedDB for online/offline functionality.

## The Goal
Build an installable app that meets PWA Standards and which allows users to enter and visualize financial transactions.

## What I Did
1. Created an MongoDB Atlas cluster, to which a database was added.
2. Created a Transaction schema using Mongoose to store user input when online.
3. Built a database in IndexedDB that holds data in the objectStore while offline, and which bulk adds data to the MongoDB database when back online.
4. Added service worker to handle data cache.
5. Wrote web manifest and edited icons to meet PWA requirements
6. Built api and html navigation routes
7. Deployed to Heroku

## Live Site
https://infinite-beach-18117.herokuapp.com/

![budget tracker screenshot](https://github.com/CorrinneW/homework-18/blob/main/public/images/Budget-Tracker-Screenshot.png)


## License

MIT License
![test](https://img.shields.io/apm/l/test)

