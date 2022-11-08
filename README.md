# nycu_sdnnfv2022_lab6_init

## Topo

![](https://i.imgur.com/elPbpY1.png)

## Perpare Environment

1. make environment
```shell=
make
```

2. test environment
```shell=
docker exec -it h1 ping 172.18.0.2 -c 3
```

## Clear Environment

1. clear environment
```shell=
make clean
```