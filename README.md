![image](https://cirquity.com/img/logo-small.png)

# Node-Cryptonote-Util

Supported on the following platforms:

* Linux 64-bit
* Windows 64-bit

## Dependencies

* NodeJS (https://nodejs.org/) v6/8/10
* Boost (http://www.boost.org/)

## Installation Instructions

### *Nix

```bash
sudo apt-get install libboost-all-dev
git clone https://github.com/cirquity/cirquity-cryptonote-util
cd cirquity-cryptonote-util
npm install && npm test
```

### Windows

#### Prerequisite

Read very carefully if you want this to work right the first time.

1) Open a *Windows Powershell* console as **Administrator**
2) Run the command: `npm install -g windows-build-tools --vs2015`
   ***This will take a while. Sit tight.***
   
Once the prerequisites are complete, proceed with the following:

```bash
cd <your node-cryptonote-util directory>
npm install && npm test
```
