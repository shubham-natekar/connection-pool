# Connection pool

## Introduction

	- In this application user can create their account and login to application.
	- I have created the below api :
		- ' / '      Home         	method GET
		- ' /users ' Create User	method POST
		- ' /users ' Show Users 	method GET
		- ' /login ' Login User		method POST
	- I have created connection-pool script inside the "api/controllers/base.go" . 

## Requirement

	- docker
	- docker-compose 


## Steps to run

1. Clone the repo " https://github.com/shubham-natekar/connection-pool " .  
2. Stop host machine services (postgresql/mysql/nginx). 
    eg.sudo service postgresql stop .
3. Open .env file and set username and password for postgresql.
4. Run the app.
    - cd connection-pool.
    - docker-compose up.
