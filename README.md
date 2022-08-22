# Social App

## Back-end setup

### Install Dependencies

- Go to back-end folder with `cd back-end` on your terminal.
- Run `npm install`

This will install all dependencies.

### Create Mongo DB Cluster

- Visit [this documentation](https://www.mongodb.com/docs/atlas/tutorial/deploy-free-tier-cluster/) and create a free cluster.

### Connect Your App to Mongo DB Cluster

- Create `.env` file.
- Paste your Mongo DB url and replace `<password>` with your password.

```env
MONGO_URL = ***YOUR MONGODB URL***
```

### Start The Server

- Run `npm start` to start the server.
- If you connect it successfully, you'll see this logs on your terminal.

```
Server is ready
Connected to Mongo
```

## Socket-IO setup

### Install Dependencies

- Go to socket-io folder with `cd socket-io` on your terminal.
- Run `npm install`. This will install all dependencies.
- Run `npm start`.

## Front-End setup

- Go to front-end folder with `cd front-end` on your terminal.
- Run `npm install`. This will install all dependencies.
- Run `npm start`.

This will start your app on `http://localhost:3000/`.
