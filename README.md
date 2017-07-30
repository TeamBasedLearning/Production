# Production

Production environment that will make the communication between the client and the server using vagrant to generate the environment and dockers to run the microservices

Tutorial:

* Upload virtual machine: ```vagrant up```
* Enter the virtual machine: ```vagrant ssh```

Server:

* Inside the machine will have two folders, one is the client and the other the server, enter the client and upload the docker:

```
cd Service/tbl
make up
```

* The server will be standing at ip:port 127.0.0.1:5050, insert it in your browser.

Client:

...
