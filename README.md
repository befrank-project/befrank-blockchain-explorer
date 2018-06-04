# BeFrank-Blockchain-Explorer
Block explorer for BeFrank CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon befrankd. It should be accessible from the Internet. Run befrankd with open port as follows:
```bash
./befrankd --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=18322
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
