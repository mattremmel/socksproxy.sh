## SocksPROXY.sh

#### Description
Sets up a socks4/5 proxy using ssh

#### Usage
socksproxy [OPTION] -p {PORT}

| Option | Description |
| --- | --- |
| -h, --help | Show help and usage information |
| -v, --version | Show version information |
| -i, --interface | Set which interface to listen on (default=0.0.0.0) |
| -p, --port | Set which port to listen on |
| -e, --endpoint | Set endpoint for proxy tunnel (default=localhost) |
| -b, --background | Run proxy in background as a daemon |

#### Dependencies

- ssh

Note: Dependencies should be standard on Linux and MacOS.
