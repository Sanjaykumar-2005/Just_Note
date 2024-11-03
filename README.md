# Just_Note

## Just_Note Project
Welcome to your new Just_Note project and to the Internet Computer development community! This README provides an overview of the project, including setup instructions and important commands to help you get started.

## Prject Overview
This is a To-do list project inspired from web development course by Angela yu with react.js as frontend and Internet Computer with motoko language as backend  

## Project Directory Structure
Explore the project directory structure to familiarize yourself with the default configuration and files provided. Working with this project in your development environment will not affect any production deployment or identity tokens.

## Getting Started
 To get started with your project, you can use the following commands:

  ```bash
  cd Just_Note/
  npm i
  dfx help
  dfx config --help
  ```
  
  ### Running the Project Locally
  To test your project locally, follow these commands:
  
  Start the replica (running in the background):
  
  ```wsl(ubuntu)
  dfx start --emulator
  ```
  Deploy your canisters to the replica and generate your candid interface:
  
  ```wsl(ubuntu)
  dfx deploy
  ```
  Once the deployment is complete, your application will be available at:
  
  If you are making changes to the frontend, you can start a development server with:
  
  ```bash
  npm start
  ```
  This will start a server at http://localhost:8080, which will proxy API requests to the replica at port 8000.
