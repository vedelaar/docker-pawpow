# Nano work server

Docker container running [nano-work-server](https://github.com/nanocurrency/nano-work-server).

The container uses [distroless](https://github.com/GoogleContainerTools/distroless), the final image weights ~25Mb.<br />

## Usage

    docker run --rm -p 127.0.0.1:7000:7000/tcp pbuyle/nano-work-server --cpu-threads 4 --listen-address 0.0.0.0:7000