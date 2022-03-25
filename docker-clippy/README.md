# Run clippy in a container.

## Setup

```
docker build -t clippy .
```

## Usage

```
docker run --rm -v $(pwd):/src clippy
```
