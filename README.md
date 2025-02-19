# Docker 101 Tutorial

This tutorial has been written with the intent of helping folks get up and running
with containers. While not going too much into depth, it covers the following topics:

- Running your first container
- Building containers
- Learning what containers are running and removing them
- Using volumes to persist data
- Using bind mounts to support development
- Using container networking to support multi-container applications
- Using Docker Compose to simplify the definition and sharing of applications
- Using image layer caching to speed up builds and reduce push/pull size
- Using multi-stage builds to separate build-time and runtime dependencies

## Getting Started

If you wish to run the tutorial, you can use the following command:

```bash
docker run -dp 80:80 dockersamples/101-tutorial
```

Once it has started, you can open your browser to [http://localhost](http://localhost) or
port 80 if running on Play-with-Docker.


## Development

This project has a `docker-compose.yml` file, which will start the mkdocs application on your
local machine and help you see changes instantly.

```bash
docker-compose up
```


## Contributing

If you find typos or other issues with the tutorial, feel free to create a PR and suggest fixes!

If you have ideas on how to make the tutorial better or new content, please open an issue first 
before working on your idea. While we love input, we want to keep the tutorial is scoped to new-comers.
As such, we may reject ideas for more advanced requests and don't want you to lose any work you might
have done. So, ask first and we'll gladly hear your thoughts!
