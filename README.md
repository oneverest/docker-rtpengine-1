# build
```
docker build ./ -t rtpengine:v1.1
```

# run
```
docker run -d -p 32738-32768:32738-32768/udp -p 22222:22222/udp rtpengine:v1.1
```

# test
```
nc -u 10.10.37.145 22222
```
