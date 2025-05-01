# Incomplete HTTP Server

This is a toy http server built in Zig. It can only handle a basic "GET / HTTP/1.1" request. It is meant as an exercise in Zig so I might add more functionality later.

## Use

To try out the server, make sure you have `zig` installed and on your path, clone the repository and run
```bash
zig run src/main.zig
```

At which point you will be able to make 1 whole request to localhost:3490/ before the server quits.
