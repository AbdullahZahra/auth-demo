# Auth Demo

## Functions of the Application

- Adding New Users.
- Making sure authorized users only have access to certain pages.

## Tools Used in the Application

I used Node.js with MongoDB on WSL and Docker.

## How to Start the Application

After getting the code on your machine you can use the docker Mongo related images or you can use your own database setup.

### Installing All Dependencies

```bash
npm install
```

### Starting the Docker Containers

1. You have to have a working docker application installed on your machine.
2. Go to the compose directory.
3. Run the docker compose up command.

```bash
cd compose
docker compose up
```

### Preparing the Database

The Node.js Application will handle all the data & table creating in the database except for the database creation itself, it has to be created manually.
You can do so by using these commands in the Mongo Shell

```bash
use blog
```

### Starting the Node.js Server

```bash
npm start
```
