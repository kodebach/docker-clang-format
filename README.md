# Clang-format

Basic Alpine Linux Docker image containing a pre-built version of `clang-format`

## Usage

Using `docker`:
```bash
docker run -it -v "$(pwd)":/workdir -w /workdir --user "$(id -u):$(id -g)" kodebach/clang-format "--version"
```

Or using `podman`:
```bash
podman run -it -v "$(pwd)":/workdir:z -w /workdir kodebach/clang-format "--version"
```

(Replace `"--version"` with your `clang-format` arguments.)

## License

[MIT License](LICENSE)
