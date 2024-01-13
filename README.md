# docker-app-webfluids

WebGL Fluids - Docker App (2024)

From original: https://paveldogreat.github.io/WebGL-Fluid-Simulation/


## Download the code and Build the container
```bash
git clone https://github.com/Juli-BCN/docker-webfluids.git
cd docker-webfluids
docker build -t webfluids .
docker images
```


## Run, Test & Stop the Docker container
```bash
docker container run -d -p 80:80 docker-webfluids
curl -L http://localhost
docker ps
```

> :eyeglasses: docker container stop *CONTAINER_ID*