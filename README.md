# genki-3001

Interim testnet. 

genki-3000 died to a [state machine bug](https://github.com/tendermint/tendermint/issues/3003). 
Long live genki-3001!

Forum thread: https://forum.cosmos.network/t/genki-3000-also-gos-is-delayed-by-48-hours

The network will do a quick start, and everyone can join in later by creating a validator
on the running the chain. There is NO disadvantage if you join later - after all, testnet
tokens are worthless. Please register only if you intend to be present at genesis.

## Getting started

Download the final genesis file from `https://raw.githubusercontent.com/certusone/genki-3001/master/genesis-final.json` and store it as `$HOME/.gaiad/config/genesis.json`

Add the following seed nodes:

    148228bd2d2e155e9edb339a7d664ea1242e6177@seed01.genki.certus.one:26656,
    89d30fa17d219ace5e57fac71ae64aeca860caea@seed02.genki.certus.one:26656,
    c01a2c3977cbb0ea28ddc9721f33709bdd0f05e2@sentry1.dokia.cloud:26656,
    99f408bf741a4c5d9da2175cdf50a85b1cda6bed@sentry2.dokia.cloud:26656,
    e7d5971503a0de4b692eb9fd0887f0fe9caadcb4@sentry3.dokia.cloud:26656
