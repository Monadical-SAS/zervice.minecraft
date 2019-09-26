# zervice.minecraft

Minecraft server setup for Ubuntu.

<img src="https://i.imgur.com/hlo7dde.jpg">

- https://mcversions.net
- https://www.minecraft.net/en-us/download/server/
- https://minecraft.gamepedia.com/Tutorials/Setting_up_a_server

```bash
cd /opt
git clone https://github.com/Monadical-SAS/zervice.minecraft
cd zervice.minecraft

mkdir data/minecraft
cd data/minecraft
wget "https://launcher.mojang.com/v1/objects/fe123682e9cb30031eae351764f653500b7396c9/server.jar"

cd ../..
docker-compose up
```
