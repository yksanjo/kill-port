# kill-port

Kill whatever's running on a port.

```
$ kill-port 3000
Killed node (pid 12345) on port 3000

$ kill-port 8080 -f
Killed python (pid 67890) on port 8080
```

## Install

```bash
git clone https://github.com/yksanjo/kill-port.git
chmod +x kill-port/kill-port
cp kill-port/kill-port /usr/local/bin/
```

## Usage

```bash
kill-port <port>      # graceful kill
kill-port <port> -f   # force kill
```

## License

MIT
