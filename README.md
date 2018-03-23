# Beanstalkd Docker Container

This is a Docker image for message queue [Beanstalk](http://kr.github.io/beanstalkd/) based Alpine (~6Mb).

A few examples how to run these containers:

```sh
docker run -d --name beanstalkd slowprog/beanstalkd
docker run -d --name beanstalkd -p 11300:11300 -p 60000:60000 slowprog/beanstalkd
docker run -d -v ${PWD}:/data:rw --name beanstalkd slowprog/beanstalkd
```
