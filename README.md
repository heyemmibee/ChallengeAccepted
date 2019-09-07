# ChallengeAccepted

A self improvement app that presents the user with a 30 day challenge, daily tasks to accomplish, daily feedback/reflections to enter and an end of challenge report.

Challenge Accepted is a responsive, mobile ready, self improvement app that presents the user with 30 daily challenges, daily journal entries and a final reports feature at the end of the challege. It was inspired by the desire to create an app that created good habits and inspiration from a podcast that claimed that an activity performed daily for 30 days could instill a habit.

The app presents the user with an initial challenge announcement on the landing page and button to click if they choose to accept. Then, the app presents a motivational quote, a fitness challenge and a spirit bar to track progress. Clicking the Begin Fitness Challenge button will present the user with the day's fitness challenge.

Upon completion of the challenge, the user will be presented with the Cross The Finish Line button.  Clicking it will make the 30 day report available to the user.  This consists of a charts for body mass index, resting heart rate and daily mood and blog entry access.

## Site Preview
![Landing page top](https://github.com/SydPRetzel/ChallengeAccepted/blob/master/LandingTop.png)
*Challenge Announcement*

![Landing page bottom](https://github.com/SydPRetzel/ChallengeAccepted/blob/master/LandingBottom.png)

![Fitness page](https://github.com/SydPRetzel/ChallengeAccepted/blob/master/Fitness.png)
*Daily Fitness Challenge*

Clicking the Daily Checkin button will present the user with a form where they can input their resting heart rate,  their body mass index and their mood level.  The user can also input a blog entry for the day.

![Checkin page](https://github.com/SydPRetzel/ChallengeAccepted/blob/master/Checkin.png)
*Daily Checkin*

![Cross the finish line](https://github.com/SydPRetzel/ChallengeAccepted/blob/master/FinishLine.png)
*Cross the finish line button*

![Reports page](https://github.com/SydPRetzel/ChallengeAccepted/blob/master/Report.png)
*Final Report*

## Getting Started

This application is acessible using the link below, deployment is via Heroku

- [Launch site](https://challenge-accepted-demo.herokuapp.com/)

## Prerequisities
Clone a local copy of the git repo.

Run > npm install

Run > nodemon server

Do not worry about any initial error messages.  This occurrs as the database has no data.

Create data via your favorite mysql client.

### Seed the inspirations table.
Use the commands in the seeds.sql to populate the inspirations table.

### Seed the metrics table.
Use the commands in the metrics_seeds.sql file to populate the metrics table.

### Slide Deck
https://docs.google.com/presentation/d/1__qtbrgr5s04XlyLEhjw5T_F9ZIJHCQb2ucLBVqe8P8

## Built With
* [Handlebars](https://handlebarsjs.com/) - front end semantic template builder
* [Bootstrap](https://getbootstrap.com/docs/3.3/) - Front-end HTML, CSS, javascript framework for creating responsive web applications. 
* [JavaScript](https://www.javascript.com/) - Programming language.
* [jQuery](https://jquery.com/) - Javascript library.
* [Node.js](https://nodejs.org/en/) - Javascript Framework
* [Express.js](https://expressjs.com/) - Node Web framework
* [MySQL](https://www.mysql.com/) - Database Management System

## Contributing

Please feel free to offer any suggestions or improvements.

## Authors

* **Emily Burnaman** - [Github](https://github.com/heyemmibee)
* **Sharmila** - [Github](https://github.com/SydPRetzel)
* **Herbert** - [Github](https://github.com/herbiemolina)

