# MERN Stack Boilerplate

## Canteen Portal using MERN STACK

### BONUS PARTS
* An email is sent to buyer in case the order is accepted or the order is rejected using emailjs
* Implemented Fuzzy Search using FUSE.js

### Hosted at:
* **Backend hosted at:** https://jomato-portal.herokuapp.com/
* **Frontend hosted at:** jomatokro.surge.sh

## Installations

### Node
**For Linux:**
```bash
curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
sudo apt-get install -y nodejs
```

**For Mac:**
```bash
brew install node
```

### MongoDB
Install the community edition [here](https://www.mongodb.com/try/download/community).

### React
```bash
npm install -g create-react-app
```

**To create a new React app:**
```bash
create-react-app name_of_app
```

**To run the app, cd into the directory and do:**
```bash
npm start
```

## Running the boilerplate

**Run Mongo daemon:**
```bash
sudo mongod
```
Mongo will be running on port 27017.

**Run Express Backend:**
```bash
cd backend/
npm install
npm start
```

**Run React Frontend:**
```bash
cd frontend/
npm install
npm start
```

Navigate to http://localhost:3000/ in your browser.
