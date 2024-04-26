### How to build Dockerfile with custom name

Dockerfile can have extensions like .prod , .test, etc.
Or it can have tottally different name like: mydockerfile

To build it:
```bash
# you can use short version of argument `-f`
$ docker image build -f Dockerfile.prod . -t custom:1
# or you can use full version of argument:
$ docker image build --file="mydockerfile" . -t custom:2
```

Also, you can build from remote url
```bash
$ docker build https://github.com/madflojo/automatron.git -t automatron:1
```