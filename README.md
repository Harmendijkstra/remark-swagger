# Swagger
Generates a TAHMO test server with a swagger UI.

## Usage
Open [docker](https://docs.docker.com/) and run the following commands in a different terminals. In order to work, one has to open the directory ./scripts where the commands are in Makefile.

```sh
$ make run
$ make swagger-ui
```
The swagger UI can than be seen at http://localhost:8081/.
Since there are different servers used, one has to enable CORS. For example by downloading the [CORS chrome app](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi).
