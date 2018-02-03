# node.js base app

    git clone https://github.com/tphummel/node-app.git new-app-dir
    cd !$
    rm -rf .git
    git init
    git add . -am "inital commit"
    git remote add ...
    git push -u origin master


# node-app

[![Build Status](https://travis-ci.org/tphummel/node-app.png)](https://travis-ci.org/tphummel/node-app)
[![NPM](https://nodei.co/npm/node-app.png?downloads=true)](https://nodei.co/npm/node-app/)

# install

    npm install {{app}}

# test

💯 enforced

    npm test

# usage

    var app = require("{{app}}");

    app();
