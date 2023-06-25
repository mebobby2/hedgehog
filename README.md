# Hedgehog

## Install
mix deps.get

## Play
iex -S mix

```
Streamer.start_streaming("xrpusdt")
Naive.Trader.start_link( %{symbol: "XRPUSDT", profit_interval: "-0.01"} )

Naive.Trader.start_link( %{symbol: "XRPUSDT", profit_interval: "-0.1"} )
```

## Upto

https://book.elixircryptobot.com/enable-parallel-trading-on-multiple-symbols.html
