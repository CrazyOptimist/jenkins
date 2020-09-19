# Jenkins Server on Docker Compose

```shell
mkdir jenkins-server
git clone https://github.com/CrazyOptimist/jenkins.git jenkins-server
cd jenkins-server
cp .env.example .env
docker-compose up -d
```

You can change your host port in .env file. <br />

For more customized usage of the image, you can refer to the official [documentation](https://github.com/jenkinsci/docker/blob/master/README.md)

# License

MIT
