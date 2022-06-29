# springboot-messaging-rabbitmq
수정중

### Environment
- springboot
- jdk 11
- gradle
- RabbitMQ Broker

### RabbitMQ Broker Install
```
* MacOS
Install
- brew install rabbitmq
execution background
- brew services restart rabbitmq
GUI
- http://localhost:15672/
- ID/PW: guest
```

###  etc
- .gitignore not working
```
- git rm -r --cached . 
```
- Learn Gradle
  - [Should you include or ignore gradle-wrapper.properties](http://stackoverflow.com/questions/21762180/should-you-include-or-ignore-gradle-wrapper-properties)

### Link
* [Messaging with RabbitMQ](https://spring.io/guides/gs/messaging-rabbitmq/)
