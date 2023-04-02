# mipt-devops

## Lab 1

- [x] First lab: you have to create your own network and virtual machine using Yandex.Cloud. 

- [x] Using this machine you have to deploy Jupyter.Lab publicly available and protected by password. You have to use docker for that.

- [x] Using this jupyter you have to write code for crawling some date from the net and parsing. Collected data have to be saved as CSV files on the same machine in /opt/lab1/data folder.
Deadline: 23:59; 5 of March 2023

## Lab 2

### TODO:

- [x] You have to spin up a database near your Jupyter container using Docker Compose. This can be any database you want MongoDB or PostgreSQL for example. 
- [ ] Using this database you have to store processed data you collected earlier. (You have to extract features yout there and put them in to DB).
- [ ] As a result I want to see GitHub repo with all your source code and a working Jupyter instance where I could access your data.

### Setup

To run the containers, simply execute `docker-compose up` in the same directory as the `docker-compose.yml` file.