# loopback
loopback 镜像


## 修改 docker-compose.yml

```
替换 /source/code 为源码目录
```


## 运行之前执行 npm install

```
如果源码不在当前路径下,请替换 $(pwd)为源码实际目录
参考1.sh
docker run -v $(pwd):/usr/src/app  --rm -it xcyxiner/node:8.9.0 /bin/bash

切换到源码目录，执行 cnpm install 或者 npm install
```
