SimpleChain Network Stats
============

This is a visual interface for tracking simpleChain network status. It uses WebSockets to receive stats from running nodes and output them through an angular interface. It is the front-end implementation for [eth-net-intelligence-api](https://github.com/cubedro/eth-net-intelligence-api).

the boot nodes state of the SimpleChain network  
http://47.91.16.204:3000/

You can join the state when Sipe start with parameters :

`--metrics --ethstats yourname:simplechain@47.91.16.204:3000`


## Prerequisite
* node
* npm

## Installation
Make sure you have node.js and npm installed.

Clone the repository and install the dependencies

```bash
git clone https://github.com/simplechain-org/netstats
cd netstats
npm install
```

##Run

```bash
npm start
```

see the interface at http://localhost:3000

[travis-image]: https://travis-ci.org/cubedro/eth-netstats.svg
[travis-url]: https://travis-ci.org/cubedro/eth-netstats
[dep-image]: https://david-dm.org/cubedro/eth-netstats.svg
[dep-url]: https://david-dm.org/cubedro/eth-netstats
