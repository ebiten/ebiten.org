# ebiten.org

## Generating

Edit HTML files under `contents` and run:

```sh
go generate .
```

## Contributions

Contributions are welcome. However, if you try to contribute one or more sections or articles, please ask Hajime Hoshi <hajimehoshi@gmail.com> before writing.

## Upload WASM files

```
GOOGLE_APPLICATION_CREDENTIALS=/path/to/credentials.json go run uploadwasm.go -ebitenpath=../path/to/ebiten -upload
```

## Test on your local machine

```
go run server.go ./docs
```