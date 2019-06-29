# chrome-novnc
```
docker build -t fever/chrome-novnc ./
docker run -d --restart=always --name=chrome-novnc -p 26080:6080 -v /data/chrome-novnc:/config  fever/chrome-novnc
```
