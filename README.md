# PNPC-deploy

PNPC Hiking Project - Deploying

## Using Docker

### Open ports

Most common default open ports that can be exposed outside of the container:

- 8080 - HTTP listener
- 4848 - HTTPS admin listener

### Manually

1. `git clone git@github.com:YMonnier/PNPC-deploy.git`
2. `cp your_file.war ./data/payara/deployments` OR `cp your_file.wat ./data/payara/autodeploy`
3. `docker-compose down; and docker-compose up`
4. `http://localhost:8080/...`

### Automatic Way

#### Versions available

Version | Branch
------- | --------------
`1.0.0` | `deploy-1.0.0`

1. `git clone -b <branch> git@github.com:YMonnier/PNPC-deploy.git`
2. `docker-compose up`
3. `http://localhost:8080/PNPC/`

_[See our server source code](https://github.com/YMonnier/PNPC-server) (branch development, release-*)_

## Contributor

- [@YMonnier](https://github.com/YMonnier)

- [@stephenbellanger](https://github.com/stephenbellanger)

## License

PNPC-deploy is available under the MIT license. See the [LICENSE](https://github.com/YMonnier/PNPC-deploy/blob/master/LICENSE) file for more info.

