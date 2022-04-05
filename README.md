# Darkest Dungeon


![Screenshot](./screenshot.png 'Скриншотес')

## Start server

```
cd cmd/server
go run *go
```

## To run game

###### It will not work without running server

```
cd cmd/client
go run main.go
```

## Sprites

[DungeonTilesetII](https://0x72.itch.io/dungeontileset-ii)

---

## Commands

```
protoc --go_out=. *.proto
sh svg2icns.sh icon.svg
```
