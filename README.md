# flood-releases
Releases of FloodUI fixed for qBitTorrent https://github.com/jesec/flood

This is Simply just compiled releases of the FloodUI by jesec
To resolve issue #592 https://github.com/jesec/flood/issues/592

For using with qflood, cop the flood-linux-x64 (or arm64) into your qflood docker container, rename it to flood, and change permissions.
e.g

```shell
docker stop qflood
wget https://github.com/Jarsky/flood-releases/releases/download/v4.7.0b/flood-linux-x64
chmod 777 flood-linux-x64
docker cp ~/flood-linux-x64 qflood:app/flood
docker start qflood
```
