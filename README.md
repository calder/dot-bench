# Dot Product Benchmarks

Usage:
```sh
make naive-4k-cc && ./a.out
make algebraic-4k-rs && ./a.out
make naive-cc && ./a.out
make algebraic-rs && ./a.out
make fast-rs && ./a.out
make naive-rs && ./a.out
make mul-add-rs && ./a.out
make map-rs && ./a.out
make fold-rs && ./a.out
```

Inspect assembly:
```sh
make naive-cc && make profile
...
```
