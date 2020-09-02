# GRAYLOG

## Starter for beginners

> [https://docs.graylog.org/en/3.3/pages/installation/docker.html](https://docs.graylog.org/en/3.3/pages/installation/docker.html)


## To start this graylog

1) start docker
2) start minikube via command  (kubernetes recommend version v1.19.1)

```
  minikube start --kubernetes-version v1.19.0
```

3) then tunnel graylog with

```
minikube tunnel --cleanup
```