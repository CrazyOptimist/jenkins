# Deployment For Your Own Jenkins Server

```shell
git clone https://github.com/CrazyOptimist/jenkins.git your_dir_name
cd your_dir_name
cp .env.example .env
docker-compose up -d
```

You can change your host port in .env file.

## Deploy from docker hub using docker command line

```shell
docker run -itd -p 8080:8080 -p 50000:50000 --name jenkins_container crazyoptimist007/jenkins
```

For more customized usage of the image, you can refer to this documentation:

https://github.com/jenkinsci/docker/blob/master/README.md

# License

MIT
