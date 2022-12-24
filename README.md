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

```

- Once you've added your db config as listed above, go to the src folder from your terminal and execute `npx sequelize db:create`
```

## DB Design
  -> Flight search DB
  - Airplane Table 
  - Flight Table
  - Airport Table 
  - City Table

  - A flight belongs to an airplane but one airplane can be used as multiple flights
  - A city has many airport but one airport can belong to a city
  - One airport has many flights but one flight belongs to one airport.