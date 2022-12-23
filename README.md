# Welcome to Flights Services

## Project Setup
- Clone the project on your local
- Execute `npm install` on the same path as of your root directory of the downloaded project
- Create a `.env` file in the root directory and the following environment variable
    - `PORT = 3000`
- Inside the `src/config` folder create a new file `config.json` and then add the following piece of json


```
{
  "development": {
    "username": <Your username>,
    "password": <Your password>,
    "database": "Flights_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}

<<<<<<< HEAD
```

- Once you've added your db config as listed above, go to the src folder from your terminal and execute `npx sequelize db:create`
=======
```
>>>>>>> f2bc8ac372eef04ce1a8be342b350ecba08659fc
