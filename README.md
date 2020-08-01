<p align="center">
  <img alt="GraphQL" title="GraphQL" src="https://scontent.fcgh7-1.fna.fbcdn.net/v/t1.0-9/p960x960/88014204_2649936828568613_3134591441859248128_o.jpg?_nc_cat=108&_nc_sid=8024bb&_nc_ohc=HBRISGVuMasAX9reXJm&_nc_ht=scontent.fcgh7-1.fna&_nc_tp=6&oh=b839731d48bbf75a11dcb0416b47761c&oe=5E93FD64" width="200px" />
</p>

<h3 align="center">
  Simple comments timeline with GraphQL
</h3>

<p align="center">This repository contains a simple comments timeline to study a little bit of GraphQL.</p>

## Features
The main features are detailed below:

1. Comments list
2. Create comments
3. Delete comments

## Technologies
Now let's take a look at the technologies used to develop the features mentioned above.

### Back-End

- GraphQL
- Apollo Server
- Docker
- MongoDB
- NPM / Yarn as package managers

### Front-End

- ReactJS
- GraphQL
- Apollo React Hooks
 

## Setup
After cloning the repository, it is mandatory to install all the dependencies this software needs. You can choose your favorite package manager: Yarn or NPM.
If you're a yarn user:
```bash
yarn install
```
However, if NPM fits better for you just run the command:
```bash
npm install
```

<br />

To finish the setup, create a copy of `.env.example` file and rename it to `.env`. Choose a connection 
string the `MONGO_URL` environment variable.
<br />
I strongly recommend using Docker to place your MongoDB database into a container.


## Running the app

### Back-End

First of all you need to keep the back-end alive. From the root directory, access the server-side folder running the command
`cd server`. Once you're on the correct path, run the back-end on <b>port 4000</b>:
```bash
yarn dev
```

If you want to test your back-end, simply access `http://localhost:4000` on your browser and use the <b>Apollo Server Playground</b>,
which is a tool provided by Apollo Server to send requests to your GraphQL API. Here we have an example:

<p align="center">
  <img alt="Apollo Server Playground" title="Apollo Server Playground" src="https://scontent.fcgh7-1.fna.fbcdn.net/v/t1.0-0/p180x540/87155278_2649945801901049_1256589692871114752_o.jpg?_nc_cat=109&_nc_sid=730e14&_nc_ohc=ASWEbpnTDu8AX_qcAf5&_nc_ht=scontent.fcgh7-1.fna&_nc_tp=6&oh=1b37f94ca3c33ba5fd41e5bdb7a927ef&oe=5EB3F1DA" width="800px" />
</p>

### Front-End

Now move yourself to the front-end directory, running the command `cd client`. Then start your ReactJS app on <b>port 3000</b>:
```bash
yarn start
```
If you made this far, a new tab will be opened on your default browser. Below there's a preview of the ReactJS app ⚛

<p align="center">
  <img alt="Apollo Server Playground" title="Apollo Server Playground" src="https://scontent.fcgh7-1.fna.fbcdn.net/v/t1.0-9/87267144_2649938275235135_4867824158425219072_o.jpg?_nc_cat=102&_nc_sid=8024bb&_nc_ohc=8KaUFsu5sSYAX_NN3fm&_nc_ht=scontent.fcgh7-1.fna&oh=1ced8b68ea235b1c274ddc28f3cab87c&oe=5E99E562" width="800px" />
</p>
