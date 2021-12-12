# Fitness.Tracker

[![MIT license](https://img.shileds.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

For this assignment, the app is a fitness tracker. The fitness tracker allows the user to create a workout where they enter various exercise associated to the workout. The data can then be analyzed with an included stats page that provides insights into the details of all their workouts. In this homework assignment, the challenge is to connect the included fronted with backend that is to be built using MongoDB, Mongoose and Express.

## Table of Contents

- [Fitness Tracker](#fitness.tracker)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Features](#features)
- [License](#license)
- [Link to Deployed Application](#application)
- [Questions](#questions)

## Installation

1. Clone this Github repository

```

git@github.com:spb71/workout-tracker.git
```

2. Install all dependent npm packages

```

npm install --save

```

3. Create a MongoDB database
4. If running locally update the MONGODB_URI with your connection string in a .env file
5. If running on a server or hosting platform add the MONGODB_URI with connection string to the environment variables
6. If needed seed the MongoDB database by running `npm run seed`

## Usage

1. Run `npm start` to start the application
2. Choose **Continue Workout** to continue the last workout or **New Workout** to create a new workout.
3. At the **Add Your Exercise** page select your **Exercise Type**
4. Enter the details of your exercise and click **Complete** to complete the workout or **Add Exercise** continue to add other exercises
5. Click the **Dashboard** on the top navigation br to see stats.

A demo of the application is available at:

## Features

- Add a workout
- Add a resistance workout
- Add a cardio workout
- See a snapshot of the last workout
- See stats with charts and graphs on the overall workouts

## License

This project uses the MIT license

## Application

https://fathomless-plateau-97517.herokuapp.com/

## Author

Checkout my Github [profile](https://github.com/spb71)
