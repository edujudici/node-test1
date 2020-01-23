# Node Js

Simple project NodeJS with MongoDB + (Express | EJS | Mongoose).

## Installation

Install Node

```
npm install -g express-generator
```

Create structure new project Express

```
express -e --git nodetest1
```

Instal dependecies

```
cd nodetest1
npm install
```

Intall dependencies mongo and mongoose

```
npm install -S mongodb
npm install -S mongoose
```

Download and install MongoDB, after start mongo server with the command bellow

```bash
mongod --dbpath ~/projetos/aprendizado/node/nodetest1/data 
```

The return must be '[initandlisten] waiting for connections on port 27017'

Open new tab in our teminal and execute

```
mongo
```
A new connection will start

Create new database

```
use nodetest1
```

Start project

```
npm start
```

## Usage

In our browser access the following urls to test application, create and read registers.

```
http://localhost:3000/newuser
http://localhost:3000/userlist

```  

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.