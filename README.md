# e2e-tests WebdriwerIO

e2e-test for WebdriwerIO applications async-await mode in selenoid
## Setup

### Install software and check out the project

- Download and install Node.JS ( at least 14.X )
- Clone and checkout the github project
- Go to the terminal and execute "npm install" inside the checked out folder

## How to run the tests on windows


[How to install selenoid on windows](help/)

Make sure your selenoid is running in docker

By local url <http://localhost:8080/#/>
![](https://i.imgur.com/TXP9fi3.png)

We have two configurations with and without video recording

- without recording video
```Console
npm run test:selenoid
```
- with recording video
```Console
npm run test:chrome-selenoid
```