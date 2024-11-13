

<h1 align="center"> Stack Overflow Clone 🚀</h1> 
<p align="center">
  <a href="https://stack-overflow-clone-y1fv.onrender.com/">
    <img alt="Stack Overflow Clone image" title="Stack Overflow Clone" src="https://i.ibb.co/TKHkYnP/Whats-App-Image-2023-08-24-at-9-23-39-PM.jpg" width="450">
    
  </a>
</p>



##  Installation
<br>

To setup the project on your local environment, follow the given steps:

1. Fork the [Overlord-1/ITL-project](https://github.com/Overlord-1/ITL-project) repository.
2. Clone the repository:
```
https://github.com/<USERNAME>/ITL-project.git
```

  Replace the `<USERNAME>` with your GitHub username. 

  ### Frontend

Move to the client directory

```bash
  cd client
```

Install the necessary dependencies

```bash
  npm install
```

To start the server in development mode

```
  npm start
```

Go to `localhost:3000` to view the website.
<br>

### Backend

Move to the server directory

```bash
  cd server
```

Install the necessary dependencies

```bash
  npm install
```

Add a config.env file in the root directory and enter your MongoDb Atlas and JWT Secret key 
The format of .env file should be similar to the following
```
CONNECTION_URL = "Mongo db url"
JWT_SECRET = "This could be anything like test"
```
To start the server in development mode

```
  npm start
```

Server will start at `PORT 5000`
<br>