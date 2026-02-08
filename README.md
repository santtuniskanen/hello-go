# hello-go
Basic hello world application. Runs as a systemd service, logs "Hello, world!" to a log file.

# Build
This application can be built for both `amd64` and `arm64` architectures. Run `dpkg-buildpackage -us -uc -aamd64` (or -aarm64). Requires Golang and Debhelper.
