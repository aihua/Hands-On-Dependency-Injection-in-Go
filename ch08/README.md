# README

## Create the MySQL database

`mysql -u root -p < ./resources/create.sql`

## Create a config (use default-config.json as a base)

## Start the app

`go run acme/main.go -config ./config.json`

## Run the tests
(Customize the config and config file location as needed)

`ACME_CONFIG=$GOPATH/src/github.com/PacktPublishing/Hands-On-Dependency-Injection-in-Go/ch08/config.json go test ./...`