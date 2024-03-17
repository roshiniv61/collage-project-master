# Installation
Run the following command to clone the repository
```
https://github.com/Koushalkushi/collage-project-master.git
```
Go to ```frontend``` and ```backend``` directory to install packages
```
cd frontend
npm install
```
```
cd backend
npm install
```
# Configuration
Create ```.env``` file inside ```backend``` directory and copy the following code

```
MONGO_DB_URL=mongodb+srv://koushal:RaIITO1O1tvRPycC@cluster10.1bfaxwb.mongodb.net/?retryWrites=true&w=majority&appName=Cluster10
PORT=5000
JWT_SECRET=a random secret key eg.secretkey
FRONTEND_URL= http://localhost:5173/

CLOUDINARY_CLOUD_NAME=dyoeabklc
CLOUDINARY_API_KEY=664348938171392
CLOUDINARY_API_SECRET=mtp5jnS2sA00pqMMiYy7VNqfrno

GOOGLE_USERNAME=koushalkushi999@gmail.com
GOOGLE_PASSWORD= ofptugwqqgdbtnzi
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_SERVICE=Gmail

```
Create ```config.js``` file inside ```frontend``` directory and copy the following code
```
const API_URL='http://localhost:5000/'
export {API_URL}
```


# Run the App
Go to ```backend``` and ```frontend``` directory and start the server
```
cd backend
npm start
```
```
cd frontend
npm run dev
```

