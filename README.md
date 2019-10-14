# build
```
docker build ./ -t rtpengine:v1.1
```

# run
```
docker run -d -p 23000-23030:23000-23030/udp -p 22222:22222/udp rtpengine:v1.1
```