# puppeteer-in-docker-in-m1
Use puppeteer inside Docker in Apple Silicon M1 / M2

`docker build . --platform=linux/arm64 -t puppeteerm1 -f Dockerfile`

`docker run -it --init puppeteerm1 /bin/bash`

`node test.js # will create a screenshot of example.com in example.png`

