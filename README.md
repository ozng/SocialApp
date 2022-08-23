# **Social App**

## Screenshots

### **Login**

![Login](https://user-images.githubusercontent.com/93818025/186156571-73c93691-88f7-4551-84c8-6ad9093b70df.PNG)

### **Home**

![Home](https://user-images.githubusercontent.com/93818025/186156549-c7c3d740-5a7c-49c7-8f8a-6e8764e3c3a2.PNG)

### **Message**

![Message](https://user-images.githubusercontent.com/93818025/186156574-73a6ac85-0032-4468-b40c-d97e6100c4ee.PNG)

### **Profile**

![Profile](https://user-images.githubusercontent.com/93818025/186156543-d6d6afb7-42ca-4a89-a3ef-3794a1ab0825.PNG)

---

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
- Create `.env` file and paste `REACT_APP_PUBLIC_FOLDER = http://localhost:8800/images/`.
- Run `npm install`. This will install all dependencies.
- Run `npm start`.

This will start your app on `http://localhost:3000/`.
