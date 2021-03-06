# Jobly
Fullstack job searching and job applying app built with a React frontend, Express backend, and PostgreSQL database. It was built during my coding bootcamp at Rithm School. This repository contains two separate applications:
1) client (React frontend)
2) server (Express backend)

# Features
Jobly allows users to:
* Sign up/login  -  Authentication and authorization middleware protects certain routes so that only logged in users can view certain pages  
* Edit user profile info
* Browse and search for companies by name
* Browse and search for jobs by job title
* View the jobs posted by each company
* Click an Apply button  -  Jobly remembers which jobs the user applied to

# Getting Started on the Server 
`cd server`  
`npm install`  
`createdb jobly`  
`createdb jobly-test`  
`psql jobly < data.sql`  
`npm start`  

# Getting Started on the Client
`cd client`  
`npm install`  
`npm start`

# Authors
My pair for client side was @jonathanlei  
My pair for server side was @Win-C  

# Acknowledgments
Although I wrote a version of the backend separately, the deployed version of this app uses the backend written by Rithm School. The reason was so that each pair could start with the same codebase when building out the React frontend.