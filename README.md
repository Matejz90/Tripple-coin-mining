![](https://komarev.com/ghpvc/?username=Matejzz90&label=Tipple-coin-mining)

# What you need

*   stable preconfigured miner for Ethereum
*   ezil account (this configuration are all for ezil.me)
*   minerstat account
*   edit eth, zil and ton addresses to your own

# Tripple coin mining

### ETH + ZIL + TON ([ezil.me](https://ezil.me/) + [ton-pool.club](https://ton-pool.club))

*   ton account on [https://ton-pool.club](https://ton-pool.club)
*   lolminer

> \--algo ETHASH --pool stratum+ssl://eu.ezil.me:25443 --user 0x5Bdf14B2cCFdd66E56b0D67C82989Ff41C7B659a.zil1zld3s9w0v49qdt5alms7p840urz0zeun74k7p8 --enablezilcache --dualmode TONDUAL --dualpool https://next.ton-pool.club⁣ --dualuser EQDwesMhhsDE5Xn-BSZikJHnBqY6ZGhr6QarHyHwAERdTZLC --worker WORKER001

# Double coin mining (ETH + ZIL)

*   lolminer

> \--algo ETHASH --pool stratum+ssl://eu.ezil.me:25443 --user 0x5Bdf14B2cCFdd66E56b0D67C82989Ff41C7B659a.zil1zld3s9w0v49qdt5alms7p840urz0zeun74k7p8 --enablezilcache

*   nbminer

> \-pool ssl://eu.ezil.me:25443 -proto 2 -wal 0x5Bdf14B2cCFdd66E56b0D67C82989Ff41C7B659a.zil1zld3s9w0v49qdt5alms7p840urz0zeun74k7p8 -worker WORKER001

*   trex  (remove --mt 4​ flag if you have problems)

> \-a ethash -o stratum+ssl://eu.ezil.me:25443 -u 0x5Bdf14B2cCFdd66E56b0D67C82989Ff41C7B659a.zil1zld3s9w0v49qdt5alms7p840urz0zeun74k7p8 -p x -w WORKER001--extra-dag-epoch 0 --mt 4​

*   phoenix-eth (remove -straps 2 flag if you have problems)

> \-pool ssl://eu.ezil.me:25443 -proto 2 -wal 0x5Bdf14B2cCFdd66E56b0D67C82989Ff41C7B659a.zil1zld3s9w0v49qdt5alms7p840urz0zeun74k7p8 -worker WORKER001 -straps 2​

# How to get ETH, ZIL and TON wallet adress

*   for ETH is primary choice metamask
*   for ZIL go to binance, click deposit, find ZIL and check your deposit address. This is your ZIL address, what you use in minerstat.
*   for TON you need to download wallet app. Stick to open source wallets like: [https://github.com/ton-blockchain/wallet-desktop/releases](https://github.com/ton-blockchain/wallet-desktop/releases)

# Sources

> [https://minerstat.com/help/how-to-dual-mine-eth-and-ton-with-lolminer](https://minerstat.com/help/how-to-dual-mine-eth-and-ton-with-lolminer)
> 
> [https://ezil.me/](https://ezil.me/)
