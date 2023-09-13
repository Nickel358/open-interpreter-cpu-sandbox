# open-interpreter-cpu-sandbox
This provides **open-interpreter** docker sandbox.

In this sandbox, only the CPU is available. GPU is **not** available.
## Setup
### Docker build
```shell
docker build -t open-interpreter-sandbox .
```

### Docker run
```shell
docker run -it --rm open-interpreter-sandbox
```

### Run open-interpreter
```shell
root@hostname:/# interpreter --local
```