# Refresher implementation

## Setup
1. Create a new directory and change directory into it.
2. Create a file called ```character.js```
3. Create a file called ```planet.js```
4. Create a file called ```index.js```
5. run ```npm init -y```
6. run ```npm install axios```
7. require ```axios``` in ```index.js```.

## Instructions
### character.js
1. Create a class called Character in the ```character.js``` file.
2. Define a constructor method that takes parameters ```name, height, mass, gender```
3. Export this class
### planet.js
1. Create a class called Planet in the ```planet.js``` file
2. Define a constructor method that takes parameters ```name, gravity, population```
3. Export this class
### index.js
1. Import both ```character.js``` and ```planet.js```
2. Define a ```function``` named ```createObject``` that takes 2 arguments ```type, id```
3. If the ```type``` argument is equals to 'planet' you will make an asynchronous request to the Star Wars api to get a planet with id equals to the ```id``` argument. After the request resolves create a new instance of the ```Planet class``` with the data you received from the request.
5. If the ```type``` argument is equals to 'character' then make a request to the Star Wars api to build a character.
