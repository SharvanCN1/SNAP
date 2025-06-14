# SNAP

Full Stack MERN AI Image Generation App MidJourney & DALL E Clone

## Tech Stack

**Client:** React, Sweetalert2, TailwindCSS, Vite

**Server:** Node, Express, Cloudinary, Mongodb, Openai

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

**Client:**
* `VITE_SERVER_URL` your backend url

**Server:**
* `MONGODB_URL` Your mongo db url
* `OPENAI_API_KEY` your OPENAI_API_KEY 
* `CLOUDINARY_CLOUD_NAME` your cloudinary name
* `CLOUDINARY_API_KEY` your cloudinary api key 
* `CLOUDINARY_API_SECRET` your cloudinary api api secret 

## Run Locally

Clone the project

```bash
  git clone https://github.com/SharvanCN1/SNAP.git
```
**Client:**
````bash
cd client
npm install
# <Create .env appropriately>
npm run dev
````
**Server:**
````bash
cd server
npm install
# <Create .env appropriately>
npm start
````
