## Project-2: Deploy a high-availability web app using CloudFormation

### Infrastructure Diagram
![the design of the Infrastructure.](https://github.com/AhmedMattar21/ITI-Project-2-IaC/blob/master/aws-project-2-diagram.jpeg)  


### Create Network Stack
```
$ cd ITI-Project-2-IaC
$ ./create "Network-Stack" network.yml network-parameters.json
```


### Create Server Stack
```
$ cd ITI-Project-2-IaC
$ ./create "Server-Stack" server.yml server-parameters.json
```
