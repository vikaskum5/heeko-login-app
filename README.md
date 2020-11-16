## Running This App

From the home folder, run the following commands:

For the very first build:

- `$ docker-compose build`

Every time after that:

- `$ docker-compose up`

Your API server should be running at `http://localhost:3003`, your client server will be running at `http://localhost:3031` and your MySQL database will be running at: `127.0.0.1:3307`

To stop the services:

- `$ docker compose-stop`

To kill the services:

`$ docker compose-down`
