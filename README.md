# nakama-go-module
Base project for Nakama's Golang server module

## Docker
- docker compose up
- docker compose build --no-cache

## Build
- go build --trimpath --mod=vendor --buildmode=plugin -o ./data/modules/backend.so
- ./nakama --database.address postgres:localdb@127.0.0.1:5432