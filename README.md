# Smart-brain-api<br/>

This is a back-end server api.

## Run the project 

### `clone this project`

### `run` npm install

### `run` npm start

## Run the entire project
To download smart-brain front-end: [Smart-brain](https://github.com/xin0415/smart-brain)<br/>
Setup your database: CREATE TABLE users(
						id serial PRIMARY KEY,
						name VARCHAR(100),
						email text UNIQUE NOT NULL,
						entries BIGINT DEFAULT 0,
						joined TIMESTAMP NOT NULL
					);
					CREATE TABLE login(
						id serial PRIMARY KEY,
						hash varchar(100) NOT NULL,
						email text UNIQUE NOT NULL
					);<br/>
Change the db variable in the file server.js to your database information
