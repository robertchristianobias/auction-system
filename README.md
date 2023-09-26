# Auction System for Jitera

A full stack auction system created using MERN (MongoDB, ExpressJs, NodeJs) Stack

## Table of contents

- [Quick Start](#quick-start)
- [Technologies](#technologies)
- [Tests](#tests)

## Quick Start

### Clone

- Clone this repo to your local machine

### Install dependencies

- Install dependencies

```bash
npm install
```

### Setting up Proccess Environment Variables

- Make a new file with the name .env in the root folder. It should contain values for these 3 variables: `PORT`,`MONGO_URI`,`JWT_SECRET`.
- If you want to enable image uploading create a Cloudinary account and enter your Cloundinary API key, Cloud Name and API Secret into the variables `API_KEY`,`CLOUD_NAME`,`API_SECRET`. (Optional)

### Run the application

```bash
npm run development
```

Open [localhost:3000](http://localhost:3000/) in the browser