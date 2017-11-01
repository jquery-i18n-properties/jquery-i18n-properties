# jQuery.i18n.properties - Publish in NPM

## Configure the machine to deploy

The next steps just need be done in tehe first time

### Install nodeJS
Follow the next steps to install nodejs

``sudo wget https://nodejs.org/dist/v8.8.1/node-v8.8.1-linux-x64.tar.xz``
``sudo tar -xJf node-v8.8.1-linux-x64.tar.xz -C /opt``
``sudo mv /opt/node-v8.8.1-linux-x64/ /opt/nodejs``

Configure as Global access
``sudo ln -s /opt/nodejs/bin/node /usr/local/bin/node``
``sudo ln -s /opt/nodejs/bin/npm /usr/local/bin/npm``

### Install npm(local)
Update the npm:

``sudo npm install npm@latest -g``

### Create a user in npmjs.com

https://docs.npmjs.com/getting-started/publishing-npm-packages

Having a user enter with commands:
``npm adduser`` - this will create a file .npmrc in your home with connection and hash to auth.

## Publish new Version

The next steps is for publish a new version on npmjs.com

### Change version

Open the file package.json and change the version to new one; 

OR

use the command ``npm version <NEW_VERSION_NUMBER>`` like this ``npm version 1.2.3`` the new version is 1.2.3

### Publish

Open terminar (in project directory) and run:

``npm publish``

### Validate

Open browser and access:

``https://www.npmjs.com/package/jquery-i18n-properties``

See new version there.

