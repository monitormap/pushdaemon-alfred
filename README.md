# README

## Install

```
npm install;
cp config_example.json config.json;
```
## Konfiguration

```
{
	"passphrase":"test", //Passphrase for authentification to server
	"url_socket":"http://localhost:8080", // Url of server
	"socket_alfred":"/var/run/alfred.sock" // Socket-Parameter of alfred
}
```

## Start

```
npm start;
```


## Developing

### Install

```
npm install;
ln -s config_example.json config.json;
```
