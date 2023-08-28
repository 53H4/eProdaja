Project from Faculty of Information Technologies - Software development II

Visual Studio 2022
SQL Server 2017+
.NET 6


-- Install Docker Desktop

* DOCKER SQL IMAGE https://hub.docker.com/_/microsoft-mssql-server

    docker pull mcr.microsoft.com/mssql/server:2017-latest
    docker run -e 'ACCEPT_EULA=Y' -e 'QWEasd123!' -p 1434:1433 -d mcr.microsoft.com/mssql/server:2017-latest
	

Usefull docker commands:

docker build -t eprodaja-api .

docker run -p 5192:5192 --name eprodaja-api-container eprodaja-api


docker image rm eprodaja-api --force


docker-compose up --build