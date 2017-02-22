# home

## installation instructions

- install https://nodejs.org/en/

```
set -ex

curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -
sudo apt-get install -y nodejs
```

- install further

```
mkdir -p /opt/code/varia/nodejs_tests
cd /opt/code/varia/nodejs_tests

npm install -g express-generator

#create example website
express --view=pug myapp_express
#install dependencies:
cd myapp_express && npm install
echo TO: run the app:
echo DEBUG=myapp-express:* npm start
cd ..
#angular
npm install -g angular-cli

#raml to md
npm install -g ramltomd

# npm install osprey -g


```
