# fuse-python

Worked on 2023-08-14

```sh
# Only works on Linux unfortunately, not Mac OS
# TODO: create a simple docker image
git clone git@github.com:libfuse/python-fuse.git

sudo python3 setup.py install

mkdir /tmp/hello
python3 hello.py /tmp/hello
```

Docker image you could create from: https://github.com/sarnobat/docker_images/blob/main/helloworld/Dockerfile
