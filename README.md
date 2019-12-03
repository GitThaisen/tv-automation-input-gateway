# Sofie: The Modern TV News Studio Automation System (Input Gateway)
An application for piping user input into the [Sofie Server Core](https://github.com/nrkno/tv-automation-server-core)

This application is a part of the [**Sofie** TV News Studio Automation System](https://github.com/nrkno/Sofie-TV-automation/).


## Usage
```
// Development:
npm run start -host 127.0.0.1 -port 3000 -log "log.log"
// Production:
npm run start
```

**CLI arguments:**

| Argument  | Description | Environment variable |
| ------------- | ------------- | --- |
| -host  | Hostname or IP of Core  | CORE_HOST  |
| -port  | Port of Core   |  CORE_PORT |
| -log  | Path to output log |  CORE_LOG |
| -id   | Device ID to use | DEVICE_ID |

## Installation for dev

* yarn
* yarn build
* yarn test

### Dev dependencies:

* yarn
	https://yarnpkg.com

* jest
	yarn global add jest

