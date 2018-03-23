# About secureBoxNmap

secureBoxNmap is a self contained µService utilizing the Nmap Networkscanner for the secureBox Application.

## Configuration Options

To configure this service specify the following environment variables:

| Environment Variable       | Value Example         |
| -------------------------- | --------------------- |
| ENGINE_ADDRESS             | http://securebox/rest |
| ENGINE_BASIC_AUTH_USER     | username              |
| ENGINE_BASIC_AUTH_PASSWORD | 123456                |

## Development

### Local setup

1.  Clone the repository
2.  Install the dependencies `npm install`
3.  Run localy `npm start`

### Test

To run the testsuite run:

`npm test`

### Build

To build the docker container run:

`docker build -t CONTAINER_NAME .`
