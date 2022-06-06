# Running Locust with Docker

```
https://docs.locust.io/en/1.5.2/running-locust-docker.html#running-locust-with-docker

比较有趣的是 他 光设置 locustfile还没用， 必须要 特定的一个 目录 写成 docker run -p 8089:8089 -v $PWD:/mnt/locust locustio/locust -f /mnt/locust/locustfile.py

很奇怪 

```
# Running Locust without Docker

```
locust -f load_test_easy_crm.py

```
