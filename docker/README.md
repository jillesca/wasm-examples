## Docker hello world

```bash
$ docker run \
  --runtime=io.containerd.wasmedge.v1 \
  --platform=wasi/wasm \
  secondstate/rust-example-hello
```

<https://docs.docker.com/desktop/wasm/>
