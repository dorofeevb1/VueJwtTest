Clone the repo and then install the server submodule and dependencies.

git submodule update --init
cd server
npm install
cd ..
npm install
Once the application scripts are in place, start the server (which will provide the quotes) using:

node server/server.js
Afterwards, open a second Terminal window and run the webpack development server. It will watch for changes with hot reloading:

npm run dev
