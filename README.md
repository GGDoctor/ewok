# EWOK
## Required Software
Git
<br>
npm
<br>
Docker
## To run: 

Download the source code from here.
../ > git clone bjhufstetler/ewok.git
<br>
Run this command to load node_modules. 

DO NOT run "npm audit fix --force" it will break the dependencies.
../ewok/api > npm i
<br>
DO NOT run "npm audit fix --force" it will break the dependencies.
../ewok/ui > npm i
<br>
../ewok > docker compose up
<br>
In a seperate command promt naviage to "../ewok/ui" and run the program using "npm run build" or "npm start" to run the ui portion of the project
<br>
### All credit to the origional creator of this program.