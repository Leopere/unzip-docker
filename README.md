# unzip-docker
Unzip things without installing unzip using docker, kind of moot in most cases but great if you don't want to install stuff on hosts.

## Usage Example

```
docker run -v $(pwd)/:/data --rm leopere/unzip-docker ./chainquery.zip
```

The usage example extracts a zip archive that you have in a volume or on the host filesystem in your current working directory on the host.
