# Bitcask
## Goals
- [ ] low latency per item read or written
- [ ] high throughput, especially when writing an incoming stream of random items
- [ ] ability to handle datasets much larger than RAM w/o degradation
- [ ] crash friendliness, both in terms of fast recovery and not losing data
- [ ] ease of backup and restore
- [ ] a relatively simple, understandable (and thus supportable) code structure and data format
- [ ] predictable behavior under heavy access load or large volume
- [ ] a license that allowed for easy default use in Riak
## Reference's
- [Bitcask - By Justin Sheehy, David Smith](https://riak.com/assets/bitcask-intro.pdf)
- [bitcask-hs - By BRonen](https://github.com/BRonen/bitcask-hs/tree/main)
