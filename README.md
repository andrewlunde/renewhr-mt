# renewhr-mt

```
npm install -g mbt

mbt --version

cf install-plugin ~/Downloads/multiapps-plugin-non-static.osxarm64 -f

cf plugins

multiapps            3.2.2     mta                                                  Display health and status for a multi-target app

node --version
v18.5.0

nvm install v18.12.1
nvm use v18.12.1

node --version
v18.12.1

npm install --global @ui5/cli

ui5 --version

ui5 --version
3.8.0


cf --version
cf version 8.7.5+8aa8625.2023-11-20

cds --version
@sap/cds: 6.8.2
@sap/cds-compiler: 3.9.2
@sap/cds-dk: 6.8.2
@sap/cds-foss: 4.0.1
@sap/cds-mtx: -- missing --
@sap/cds-mtxs: 1.8.2
@sap/eslint-plugin-cds: 2.6.3
Node.js: v18.12.1
home: /Users/i830671/.nvm/versions/node/v18.5.0/lib/node_modules/@sap/cds-dk/node_modules/@sap/cds

npm install --global @sap/cds-dk
cds --version
@sap/cds: 6.8.2
@sap/cds-compiler: 3.9.2
@sap/cds-dk: 6.8.2
@sap/cds-dk (global): 7.5.1
@sap/cds-foss: 4.0.1
@sap/cds-mtx: -- missing --
@sap/cds-mtxs: 1.8.2
@sap/eslint-plugin-cds: 2.6.3
Node.js: v18.12.1
home: /Users/i830671/.nvm/versions/node/v18.5.0/lib/node_modules/@sap/cds-dk/node_modules/@sap/cds


npm install --global @sap/cds-mtx

added 79 packages, and audited 80 packages in 7s

cds --version
@sap/cds: 6.8.2
@sap/cds-compiler: 3.9.2
@sap/cds-dk: 6.8.2
@sap/cds-dk (global): 7.5.1
@sap/cds-foss: 4.0.1
@sap/cds-mtx: -- missing --
@sap/cds-mtxs: 1.8.2
@sap/eslint-plugin-cds: 2.6.3
Node.js: v18.12.1
home: /Users/i830671/.nvm/versions/node/v18.5.0/lib/node_modules/@sap/cds-dk/node_modules/@sap/cds

install the SAP Fiori tools - Extension Pack extensions for VS Code:


nvm use v18.12.1
npm install --global yo



ver=$(cf buildpacks | grep nodejs | cut -d '-' -f 4 | cut -d '.' -f 1-3) ; echo ; echo "Browse to this page for nodejs versions available in this buildpack." ; echo ; echo "https://github.com/cloudfoundry/nodejs-buildpack/releases/tag/$ver" ; echo

Browse to this page for nodejs versions available in this buildpack.

https://github.com/cloudfoundry/nodejs-buildpack/releases/tag/v1.8.20
v1.8.9

Packaged binaries:

name	version	cf_stacks
...
node	20.9.0	cflinuxfs3

nvm install v20.9.0

npm install -g yo
npm install -g mbt
npm install -g @ui5/cli
npm install -g @sap/cds-dk
npm install -g @sap/cds-mtx

mkdir tutorial
mkdir cpapp
git clone https://github.com/SAP-samples/cloud-cap-risk-management tutorial


cds init cpapp
Creating new CAP project in ./cpapp

Adding feature 'nodejs'...

Successfully created project. Continue with 'cd cpapp'.
Find samples on https://github.com/SAP-samples/cloud-cap-samples
Learn about next steps at https://cap.cloud.sap


nvm use v20.9.0

nvm use v18.18.2
npm install -g mbt
npm install -g @ui5/cli
npm install -g @sap/cds-dk
npm install -g @sap/cds-mtx


cds add mta
cds add multitenancy,hana,xsuaa

cd mtx/sidecar/
npm i --omit=dev
cd ../..

mtb build

cf deploy mta_archives/cpapp_1.0.0.mtar

cf logs cpapp-mtx

cf undeploy cpapp -f --delete-services


```