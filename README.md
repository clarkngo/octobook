# Welcome to Octobook

# Installation
```
git clone git@github.com:clarkngo/octobook.git
cd octobook
npm install
```
# Build Commands
```
npm run build
npm run watch # continously build
npm run clean # start fresh
```
After running build or watch, open up index.html in a browser.
# Terminology
Model

Provider

# Tech Stack
* [Node.js](https://nodejs.org) / [Express](https://expressjs.com) for our backend using JavaScript/TypeScript
* [Postgres](https://www.postgresql.org) with [Sequelize ORM](https://sequelize.org)

## Schema
<details>
<summary>Expand to view a diagram illustrating the proposed schema for Octobook.</summary>
<br>

## User stories so far

Our goal is to keep things simple and not reinvent wheels. So far we have only two user roles: participants and chapter organizers, both of which are users.
### As a user

- I can open a registration page where I can sign up with email and password.

- I can log in with my email and password or I can log in with social login via Google.

- I can see my account page where I can reset my password if I've registered with email and password. Otherwise I'll see a link to my Google profile.

- I can log out.

### As a provider

- I can see a calendar and create a job posting
  - Add the following info:
    - Age range
    - Disease
    - Day/Time
    - Notes
- I can see a calendar and see `models` that are available with % match from criteria

- I can see a list of `models` I can book

### As an model

- I can see a calender and register my available dates

## Roadmap

1. Design the schema.
2. Set up the API endpoints.
3. Build the web client and let other developers use the API to build mobile clients and voice interface clients.

# Support
Bug reports and feature requests can be filed here:

[File Bug Reports and Features](https://github.com/clarkngo/octobook/issues)
# License
Released under the MIT license.

# Copyright
&copy; Copyright 2019 Clark Jason Ngo. All Rights Reserved.
