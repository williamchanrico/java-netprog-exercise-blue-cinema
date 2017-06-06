# java-netprog-exercise-blue-cinema
Blue Cinema multicast example in Java

Note that the multicast ports and address are hard coded:
```java
  final int SERVER_PORT = 8888;
  final int CLIENT_PORT = 7777;
  final String MCAST_ADDR = "224.0.0.3";
```

## Usage
### Server
```
$ javac BlueCinemaServer.java
$ java BlueCinemaServer
```
### Client
```
$ javac BlueCinemaClient.java
$ java BlueCinemaClient
```
### Used Compiler
```
$ javac -version
javac 1.8.0_121
```

## Preview
![screenshot](screenshot.png?raw=true "Screenshot")
