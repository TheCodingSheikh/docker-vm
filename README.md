# Docker VM

## Installation and usage

#### 1. Clone the repo
```git clone https://github.com/TheCodingSheikh/docker-vm.git```

#### 2. Build and run the docker compose
```docker compose up -d --build```

#### 3. access the container through ssh
```ssh docker@localhost -p 22```

password id `docker`

thats it! now use it as a normal linux machine to clone repos and run them safely.
if you run any application inside the container, map the ports in the docker compose to expose it to your local machine, re-build and run

*all files download inside the container will be saved inside a folder `data` in the current directory so you data shall be persistent*