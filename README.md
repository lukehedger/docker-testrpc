# Dockerized Ethereum `testrpc`

> Docker image for Ethereum RPC client for testing and development

## Image

- Runtime: Node.js (latest)
- Libraries: testrpc (latest)

## Pull
```
docker pull levelout/testrpc
```

## Usage
```
docker run -d -p 8545:8545 testrpc
```

See [`ethereumjs/testrpc`](https://github.com/ethereumjs/testrpc) for available options.
