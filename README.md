# pwd

Print the current directory.

## Installation

The first need [Go](https://go.dev/doc/install) installed, then you can use the below
command to install `pwd`.

```bash
go install github.com/no-src/pwd@latest
```

Or manually compile and reduce the size of the program.

```bash
mkdir -p $GOPATH/src/github.com/no-src
cd $GOPATH/src/github.com/no-src
git clone https://github.com/no-src/pwd.git
cd pwd
go build -ldflags="-s -w"
wget https://github.com/upx/upx/releases/download/v4.0.2/upx-4.0.2-amd64_linux.tar.xz
tar -xvf upx-4.0.2-amd64_linux.tar.xz
./upx-4.0.2-amd64_linux/upx pwd
```