# docker-monero

[![](https://images.microbadger.com/badges/image/babim/monero.svg)](https://microbadger.com/images/babim/monero "Get your own image badge on microbadger.com")

  # either run in foreground
  `docker run -it -v /monero/chain:/root/.bitmonero -v /monero/wallet:/wallet -p 18080:18080 babim/monero`

  # or in background
 `docker run -it -d -v /monero/chain:/root/.bitmonero -v /monero/wallet:/wallet -p 18080:18080 babim/monero`
