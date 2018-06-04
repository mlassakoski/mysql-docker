<h1 align="center">Mysql Docker</h1>

>This repo serves a mysql database running on docker 

[Setup and install](#setup-and-install) | [Usage](#usage) 

## Setup and install

Your can fork this repo clone or simply download the `.zip` bundle with the contents inside.

#### Environment installation

To run this project you'll need Docker. You can skip this step if you already have Docker installed. 

1. Download and install [Docker](https://www.docker.com/get-docker) 

#### Project installation

```
cd <mysql-docker>

docker-compose up
```

## Usage 


 Clone the project from github
```
  https://github.com/mlassakoski/mysql-docker.git
```
Open a terminal and use `cd` to enter into directory where you cloned the project.

You can configure the database name and password editing the `docker-compose.yml` file. After it, inside project directory execute:

```
docker-compose up
```

Now your database is running on `http://localhost:3306/`

connect using terminal 
- mysql -h 127.0.0.1 -u root -p


Done!


## Credits

*Mauricio Lassakoski

## License

* MIT