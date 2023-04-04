# Canvas: Real-time drawing board app 📝 

Canvas is a collaborative drawing application that allows multiple users to draw on the same board and see real-time changes. This repository contains the frontend code for the Canvas project.

## Features 🖌

Real-time updates: Users can see real-time updates simultaneously and create/modify collaborative drawings.
Authentication: Users are authenticated at login by encrypting account information via bcrypt and salt.
Frontend integration: React Sketch Canvas library is integrated as a basic template for the frontend.
Custom database schema and REST API: Active Record and Sinatra are used to model the database schema and REST API.


## System dependencies: 
Ruby: 2.7.4
Node: 16.17.1
PostgreSQL: 12.12

## Configuration:

#### Install packages
###### bundle install
###### npm install --prefix client


#### Database creation & initialization
###### rails db:create db:migrate


#### How to run the test suite
###### rails s
###### npm start --prefix client
###### Then, open localhost:4000 on your browser.

## Repository 🔍 

This repository contains the FrontEnd code for the Canvas project. The Backend code can be found here. [https://github.com/Kailin168/CanvasProjectBE]
