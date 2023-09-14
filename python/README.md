## Wasmer

```bash
wasmer run python/python -- -c "for x in range(5): print(x)"
```

```bash
╰─ cat wasm/test.py
print('hello world')

╰─ wasmer --net python/python --mapdir=./wasm:./wasm -- wasm/test.py
hello world
```

<https://github.com/wapm-packages/python>
