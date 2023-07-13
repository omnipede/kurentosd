# kurentosd

Kurento send data channel demo

# Requirements

* jdk >= 19
* bower

# Run

* Start kurento server
```shell
$ sh ./start.sh
```

* Install bower js static dependency
```shell
$ cd src/main/resources/static
$ bower install
```

* Run application server
```shell
$ ./gradlew bootRun -x test
```

* http://localhost:8443/index.html 접속

# Code
* [Server side](https://github.com/omnipede/kurentosd/tree/main/src/main/kotlin/io/omnipede)
* [Client side](https://github.com/omnipede/kurentosd/blob/main/src/main/resources/static/index.html)
