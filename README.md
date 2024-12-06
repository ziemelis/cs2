# cs2go

https://go.dev/doc/install


ENV
   ```
   set GOOS=windows
   set GOARCH=amd64
   ```
Build
   ```
   go build -ldflags "-s -w"
   ```
Dependencies
   ```
   go get github.com/lxn/win
   go get golang.org/x/sys/windows
   go mod tidy
   ```

