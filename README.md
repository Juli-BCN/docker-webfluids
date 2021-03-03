# docker-app-webfluids

WebGL Fluids - Docker App (2021)

From original: https://paveldogreat.github.io/WebGL-Fluid-Simulation/

## Install Docker on Amazon Linux 2
> sudo yum update -y

> sudo amazon-linux-extras install -y docker

> sudo service docker start

> sudo usermod -a -G docker ec2-user

> sudo systemctl enable docker

> docker info



## Download the code and Build the container
> sudo yum install -y git

> git clone https://github.com/Juli-BCN/docker-webfluids.git

> cd docker-webfluids

> docker build -t docker-webfluids .

> docker images



## Run, Test & Stop the Docker container
> docker run -d -p 80:80 docker-webfluids

> curl -L http://localhost

> docker ps

> :eyeglasses: docker stop *CONTAINER_ID*