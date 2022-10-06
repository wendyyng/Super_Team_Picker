# Super Team Picker

Super Team Picker is a web application built with Node and Express that allows users to:
- Create, edit and delete cohorts
- Randomly generate teams based on selected methods: team count/ number per team

## Demo Link
YouTube: https://youtu.be/XdJQSqc3XBE

## Final Product

!["Home"](https://user-images.githubusercontent.com/71687298/194415131-4d969ce7-e2cd-47f3-a2a7-2ad2c28ba668.png)
!["Cohorts"](https://user-images.githubusercontent.com/71687298/194415190-eaff97b1-f958-4d75-ab75-96285ff1b4a2.png)
!["New Cohort"](https://user-images.githubusercontent.com/71687298/194415243-ad16f9b2-6664-4034-8f29-d4db805913d0.png)
!["Assign Teams - Number Per Team"](https://user-images.githubusercontent.com/71687298/194417456-018c0f3b-be36-4a84-a54e-303aabbcba90.png)
!["Assign Teams - Team Count"](https://user-images.githubusercontent.com/71687298/194416205-9f85f575-e317-424d-800c-6b871225548c.png)

## Dependencies
- Node.js
- Express
- EJS
- body-parser
- knex
- method-override
- morgan
- pg

## Dev Dependencies
- nodemon

## Styling
- Bootstrap v5.1.3

## Getting Started
- Install all dependencies using the `npm` command
- Set up database using Knex and PostgreSQL
- Run the server using `npm start` command


# File Structure

## Server and Router
- index.js
- cohorts.js
- assign.js

## Views
- footer.js
- formInput.ejs
- header.ejs
- edit.ejs
- index.ejs
- new.ejs
- show.ejs
- home.ejs
