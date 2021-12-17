# node.js-pm2-example

This project is an easy example for pm2 & loadtest in Node.js.

Please be noticed, I install all package locally in this project.

So if you want to directly use pm2 and loadtest command, you should use 

**node_module/.bin/pm2 ...** and **node_module/.bin/loadtest ...**

Or just install pm2 and loadtest globally.

# Start project

### master
```=bash
git clone https://Hakalon@git.ntust.ml/Hakalon/node.js-pm2-example.git
cd node.js-pm2-example // or your project directory name
npm install // or if you have yarn, use yarn install
npm start
```

# Remarks

There are some script you can use:

### pm2
```=bash
// delete this pm2 service
npm run del

// Show status of this pm2 service
npm run show

// Show log messages recived by this pm2 service
npm run log
```

If you want to understand more, you can checkout package.json and [here](http://pm2.keymetrics.io/docs/usage/quick-start/)

### loadtest
```=bash
// sending 1000 requests to localhost by loadtest
npm run test
```