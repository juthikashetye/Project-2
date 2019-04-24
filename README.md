# Triviosa

## Description

* Triviosa is a single player trivia game.

* On sign-up the user creates an account with a unique username and selects a team of their choice. The player is then able to select a difficulty level to play a quiz related to the topic they choose.

* Each question correctly answered adds random points to both your and your team's score. At the end of each game, you can see your score, rank and the overall ranking of your team. You can also checkout the Leaderboard to see the scores and rankings of all the players and teams.

This game was developed as a project for the UC Berkeley Coding Bootcamp, San Francisco.

## Packages Used

* [Require](https://www.npmjs.com/package/require)

* [MySQL](https://www.npmjs.com/package/mysql)

* [Express](https://www.npmjs.com/package/express)

* [Body-Parser](https://www.npmjs.com/package/body-parser)

* [Method-Override](https://www.npmjs.com/package/method-override)

* [Express-Session](https://www.npmjs.com/package/express-session)

* [Cookie Parser](https://www.npmjs.com/package/cookie-parser)

* [MD5](https://www.npmjs.com/package/md5)

* [DotEnv](https://www.npmjs.com/package/dotenv)

## System Requirements

1. NodeJS - version 10 and up

2. MySQL - version 8.0 

## Setting Up The Application

### Cloning The App

![Clone The App](public/assets/screenshots/download.png)

### Install The Packages Listed 

* In your terminal, navigate to the Project-2 folder and run `npm install` (see Figure 1)

* After running `npm install`, the packages listed above should be downloaded inside the `node_modules` folder.

* In case you don't see the packages in `node_modules`, use the package links mentioned above to manually install the required packages. (see Figure 2)

![Installing Packages](public/assets/screenshots/packages.png)
<p align="center" style="color:gray;font-size:12px;"><i>Figure 1: Package Installation</i></p>

![Node Modules Folder](public/assets/screenshots/modules.png)
<p align="center" style="color:gray;font-size:12px"><i>Figure 2: The yellow-lined modules are expected to be inside the node_modules folder for the app to work.</i></p>

### Building Your Database

* In your terminal navigate inside the `db` folder. Then login to your **MySQL** connection
* Once logged in, run `source schema.sql` followed by `source seeds.sql` (See Figures 4a and 4b)
* SQL Version required is 8.0 and up

![Creating The Database](public/assets/screenshots/schema.png)
<p align="center" style="color:gray;font-size:12px;"><i>Figure 4a: source schema.sql</i></p>

![Creating The Database](public/assets/screenshots/seeds.png)
<p align="center" style="color:gray;font-size:12px;"><i>Figure 4b: source seeds.sql</i></p>

### Create Your `.env` File

* Navigate back to Project-2 folder and create a `.env` file. Inside this file, provide your database credentials. (See Figure 5)

![Inside Env](public/assets/screenshots/envFile.png)
<p align="center" style="color:gray;font-size:12px;"><i>Figure 5: Information inside the .env file.</i></p>

### Running The App

![Running The File](public/assets/screenshots/nodemon.png)

![The Application](public/assets/screenshots/triviosa.png)

**_Voila!_**/ You now have Triviosa running in your browser!

## Credits

www.flamingtext.com - for the logo images

www.orangefreesounds.com - for the sounds used for this game

https://www.triviaquestionss.com/ - for the questions used in the game
