# Dev Connections
A small social network for developers built with the MERN stack. Includes authentication using JWT web tokens. The app uses Redux for client-side state management.

You can check out the live project by Clicking [here](https://jealous-pea-coat-boa.cyclic.app/)

## TODO

- Better Logging
- Fetch Popular GitHub Repos

## Technologies Used

- [MongoDB](https://www.mongodb.com/)
- [ExpressJS](https://expressjs.com/)
- [ReactJS](https://reactjs.org/)
- [NodeJS](https://nodejs.org/en/)


## Quick Start

### Add a default.json file in the config folder with the following

```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run both Express & React from root

```bash
npm run dev
```

### Build for production

```bash
cd client
npm run build
```

### Test production before deploy

```bash
NODE_ENV=production node server.js
```


### Created By

 [Ali Ahmad](https://www.aliahmad.co)
