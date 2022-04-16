# Salus-Lap

Welcome to saluslap simple dashboard.

## Introduction
This project is a basic login, registeration and dashboard. Users can register and login the system then they could access the dashboard which contains a simple table of all registered users.

## Content
This repo contains the both files for the client and for the server sides, I used for the client side VueJS and TailwindCSS, for the backend I used NodeJS/Fastify and MongoDB.

## Installtion
To install and build this project you have to install the packages first for the both folders using the following command:

`npm install`

To start the development mode run this command:

`npm run dev`

## Endpoints
I provides four simple and core endpoints:

|METHOD |ENDPOINT | REQUEST BODY & PARAMS | RESPONSE |
|:--- |:--- | ---: | :---:|
|GET |  localhost:3000/users  |  | status code and List of users | 
|GET |  localhost:3000/users/:id   | id of the user  | status code and registered user |
|POST|  localhost:3000/users/register   | { username, email, password }  | status code and registered user |
|POST|  localhost:3000/users/login   | { email, password }  | status code and loged in user |
