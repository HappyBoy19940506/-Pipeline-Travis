# Running Locust with Docker

```
https://docs.locust.io/en/1.5.2/running-locust-docker.html#running-locust-with-docker

比较有趣的是 他 光设置 locustfile还没用， 必须要 特定的一个 目录 写成 docker run -p 8089:8089 -v $PWD:/mnt/locust locustio/locust -f /mnt/locust/locustfile.py

很奇怪 

2.  如何让 dockerized Locust 和 Dockerized Api 通信。 host 名字是关键。 要写成 https://[service-name]:8080

https://stackoverflow.com/questions/60550111/connection-refused-error-111-when-using-locust-for-performance-testing-against
```
# Running Locust without Docker

```
PATH : locust command not found

/Users/user/Library/Python/3.8/bin/locust --version

locust -f locustfile.py

```
