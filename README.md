# 重庆高校 Linux 上网客户端 openkeeper  

## Introduction  

- An open source implementation of Netkeeper for Linux.  

## Build & install dependencies  

```
Ubuntu: pppoe m4 libssl-dev  
Debian: pppoe m4 libssl-dev  
openSUSE: rp-pppoe m4 libopenssl-devel  
```

## Installation  

```bash
$ git clone https://github.com/Eventide/openkeeper-cli.git
$ cd openkeeper-cli
$ ./configure --prefix=/usr/local
$ make 
$ sudo make install 
```

## Usage  

- Configuration  

```bash
$ sudo ok-config
```

- Connect  

```bash
$ sudo ok
```

- Disconnect

```bash
$ sudo ok-stop
```

## Contributors  

```
Eventide    <nanjingzr@yahoo.com>
RainMark    <rain.by.zhou@gmail.com>
Stawidy     <duyizhaozj321@yahoo.com>
Wu Shuang   <qnnnnez@live.com>
```