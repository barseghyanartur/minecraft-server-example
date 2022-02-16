# Minecraft multi-player instructions

## Installation

### 1. Clone this repository

    ```shell-script
    git clone git@github.com:barseghyanartur/minecraft-server-example.git
    ```

### 2. Grab the MineCraft server

[Grab the MineCraft server](https://www.minecraft.net/en-us/download/server).

    ```shell-script
    wget -O minecraft_server.1.18.1.jar https://launcher.mojang.com/v1/objects/125e5adf40c659fd3bce3e66e67a16bb49ecc1b9/server.jar
    ```

### 3. Install Java

[Follow the instructions here](https://tlauncher.org/en/install-java.html#install-java-linux).

Or simply:

**Ubuntu**

```shell-script
sudo apt install openjdk-11-jdk
```

**Fedora**

```shell-script
sudo yum install java-11-openjdk
```

### 4. Grab the TLauncher

[Download from here](https://tlauncher.org/en/install-java.html).

```shell-script
wget 
```

## Wire-up

### Start the server

```shell-script
docker-compose up
```

### Start the client

```shell-script
./TLauncher.sh
```

### Bin

