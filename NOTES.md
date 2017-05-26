__build__:  

```bash
docker build -t d/doing . -f Dockerfile.doing
```



__run__:

```bash
docker run --rm -v $HOME/.doing:/root/ -it d/doing [CMD] # default command: help
```



