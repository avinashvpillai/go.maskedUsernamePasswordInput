# go.maskedUsernamePasswordInput
accepting username &amp; masked passwork from cmd - GO language

* linux distribution from windows 10:
Open git bash and use mentioned command OR  CMD for each OS architecture:
set GOOS=linux set 
GOARCH=amd64 
go build -o filename_linux_amdx64

set GOOS=linux
set GOARCH=386
go build -o filename_linux_x86

set GOOS=linux
set GOARCH=arm64
go build -o filename_linux_arm64

set GOOS=darvin
set GOARCH=amd64
go build -o filename_mac_amd64.dgm

default windows 10:
set GOOS=windows
set GOARCH=amd64


* build with version number:
go build -o maskedUsernamePassword_0.0.1.exe .
OR
go build -ldflags "-X main.version=v0.0.1" -o maskedUsernamePassword_0.0.1.exe .
