Run the two commands to reproduce the issue:

```sh
# use pnpm v6
$ docker build -t pnpm-v6 -f .\Dockerfile.pnpm-v6 .

# use pnpm v7
$ docker build -t pnpm-v7 -f .\Dockerfile.pnpm-v7 .
```

I also take snapshots of the results on my machine. See `./v6-result.PNG` & `./v7-result.PNG`