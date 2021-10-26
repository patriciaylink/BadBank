# Bad Bank project

## Description/Motivation 
I'm creating this project to demonstrate a three-tiered web application using the MERN Stack.  This is a banking app which will allow users to log in, then deposit and withdraw money from their account. This project will integrate a front-end app built using React with a back-end Express API & Node JavaScript server platform, that interacts with a MongoDB database.  

## Installation Guidelines 
1. Clone the project into a project directory that you've created: Run 'git clone patriciaylink/BadBank' in the terminal
2. Set up your dependencies: In order to proceed, you will need to install Node (from https://nodejs.org/en/), npm (run 'npm install') & Docker
3. Install packages & run docker: Run 'npm init', then run 'docker run -d -p 27017:27017 --name BadBankDB mongo'
4. Start the project on your local machine: Run 'npm start'. Navigate to http://localhost:3000 to view it in the browser.

## Screenshots
Create Account screen <br>
<img width="486" alt="CreateAccount screen" src="https://user-images.githubusercontent.com/78698732/138906331-bf01c96f-7a22-433d-a15e-07ffb5d41ba5.png">

Deposit screen<br>
<img width="485" alt="Deposit screen" src="https://user-images.githubusercontent.com/78698732/138906352-6b062ff7-7272-43b9-b59b-29a72b4ca8ad.png">

## Technology used:
- React
- Bootstrap
- NodeJS
- Express
- Docker
- Firebase
- MongoDB

## Features
### Current features
- Create a new user
- Deposit money into an existing user's account
- Withdraw money from an existing user's account
- Check the user's balance
- View data of all users created and transacted in the bank
### Future features
- Login using existing users

## License
MIT License
