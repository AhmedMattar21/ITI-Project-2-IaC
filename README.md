## Project-2: Deploy a high-availability web app using CloudFormation

### Infrastructure Diagram
![the design of the Infrastructure.](https://github.com/AhmedMattar21/ITI-Project-2-IaC/blob/master/aws-project-2-diagram.jpeg)  


### Build Network Stack
```
$ cd ITI-Project-2-IaC
$ ./create "Network-Stack" network.yml network-parameters.json
```


### Build Server Stack
```
$ cd ITI-Project-2-IaC
$ ./create "Server-Stack" server.yml server-parameters.json
```

### 🔥 Now we have successfully built the whole infrastructure in just seconds.
