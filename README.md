# Getting Started with NodeRED
Code samples for the webinar [Iniciación al Prototipado IoT con NodeRED](https://youtu.be/zdrnL05yft0)

1. Install locally NodeRED and contributed module Dashboard UI:
> `$ npm install`

2. Run the sample flow (CPU and memory usage):
> `$ npm start`

This command runs the following script (NodeRED with options):
> `node node_modules/node-red/red.js --settings=./settings.js flows/flow.json`

3. Run the digital clock project:
> `$ npm run digital-clock`

The command that is run by this script is:
> `node node_modules/node-red/red.js --settings=./settings.js flows/flow_digital-clock.json`

For ease of starting the following features of NodeRED have been disabled (file `settings.js`):
- NodeRED editor authentication
- NodeRED project