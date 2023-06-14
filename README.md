# simple docker mysql template

# Requirements
[docker compose](https://docs.docker.com/compose/install/linux/)

# Running
```shell
$ docker compose up
```

# Connecting
```shell
$ mysql -u root -p -h 0.0.0.0
```
another example:

```shell
$ mysql -u root -p -h 0.0.0.0 -e "show databases;"
```

