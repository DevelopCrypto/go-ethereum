# Go Ethereum over lachesis

## Note

Repo is the [github.com/ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) fork.
It should be in the same local path as original: `$GOPATH/src/github.com/ethereum/`.


## Aim

Ethereum over lachesis network and consensus.


## Changes

* Rename p2p.Server to p2p.p2pServer;
* Create p2p/interface.go with p2p.ServerInterface and p2p.Server struct;
* p2p.p2pServer implements p2p.ServerInterface;
