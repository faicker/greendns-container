[greendns](https://github.com/faicker/greendns) docker image.

## usage

```bash
docker run -it -d --rm --network=host faicker/greendns
```

Default listen is 127.0.0.1:53(see [Dockerfile](Dockerfile))

You can change listen by passing argument like "-e LISTEN=127.0.0.1:54".

See [entrypoint.sh](entrypoint.sh) for other arguments.
