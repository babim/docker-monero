# docker-monero

  # either run in foreground
  `docker run -it -v /monero/chain:/root/.bitmonero -v /monero/wallet:/wallet -p 18080:18080 babim/monero`

  # or in background
 `docker run -it -d -v /monero/chain:/root/.bitmonero -v /monero/wallet:/wallet -p 18080:18080 babim/monero`
