# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-10 19:26:54 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2525` | `0.2594` | `0.2353` | `+6.58%` |
| `ALGO-USDT` | `0.1183` | `0.121` | `0.1097` | `+4.13%` |
| `ATOM-USDT` | `1.9798` | `2.0846` | `1.917` | `-4.34%` |
| `AVAX-USDT` | `10.483` | `10.674` | `10.117` | `+2.82%` |
| `BCH-USDT` | `281.43` | `281.69` | `273.01` | `+2.59%` |
| `BTC-USDT` | `83029.8` | `83164.1` | `82282.5` | `+0.67%` |
| `CAKE-USDT` | `2.233` | `2.233` | `2.164` | `+2.61%` |
| `DASH-USDT` | `51.45` | `51.95` | `50.74` | `+0.03%` |
| `DGB-USDT` | `0.00364` | `0.003702` | `0.003369` | `+1.11%` |
| `DOGE-USDT` | `0.08614` | `0.08671` | `0.08422` | `+1.79%` |
| `DOT-USDT` | `1.2545` | `1.2965` | `1.2009` | `+3.78%` |
| `ETC-USDT` | `8.4133` | `8.5209` | `8.2317` | `+1.50%` |
| `ETH-USDT` | `2513.61` | `2517.38` | `2474.56` | `+1.18%` |
| `LINK-USDT` | `13.0674` | `13.25` | `12.6371` | `+1.82%` |
| `LTC-USDT` | `64.1` | `64.42` | `63.16` | `+0.99%` |
| `QTUM-USDT` | `1.008` | `1.019` | `0.943` | `+6.55%` |
| `SHIB-USDT` | `0.000005481` | `0.000005522` | `0.000005378` | `+1.42%` |
| `SOL-USDT` | `110.48` | `110.77` | `108.44` | `+1.07%` |
| `TRX-USDT` | `0.331` | `0.333` | `0.3306` | `-0.60%` |
| `UNI-USDT` | `7.5215` | `7.71` | `7.2298` | `+3.11%` |
| `XLM-USDT` | `0.1972` | `0.1986` | `0.1914` | `+2.33%` |
| `XMR-USDT` | `530.93` | `536` | `514.52` | `+1.52%` |
| `XRP-USDT` | `1.40468` | `1.41299` | `1.38064` | `+1.22%` |

---

## JSON Schema

Each record in `rateStatic.json`:

```json
{
    "symbol": "BTC-USDT",
    "lastPrice": "63042.8",
    "highPrice24h": "63500",
    "lowPrice24h": "62480.1",
    "changeRate": "0.0049",
    "lastUpdated": "2026-10-10 19:26:54 UTC"
}
```

`changeRate` is a fraction of the 24h open price, not a percentage: `0.0049` means `+0.49%`.

---

Hit Cryptocurrency Rate Reporter and Ticker (Auto Update)

![](https://raw.githubusercontent.com/FetchServe/Rate/media/rateStatic.png)

---

## Example Code in Various Languages

We have provided example code for utilizing the **FetchServe Rate API** in different programming languages. You can find these examples in the following pages:

- [C Example Code](https://github.com/FetchServe/Rate/wiki/C-Example-Code)
- [C++ Example Code](https://github.com/FetchServe/Rate/wiki/C-Plus-Plus-Example-Code)
- [Go Example Code](https://github.com/FetchServe/Rate/wiki/GO-Example-Code)
- [Haskell Example Code](https://github.com/FetchServe/Rate/wiki/Haskell-Example-Code)
- [JavaScript Example Code](https://github.com/FetchServe/Rate/wiki/JavaScript-Example-Code)
- [PHP Example Code](https://github.com/FetchServe/Rate/wiki/PHP-Example-Code)
- [PowerShell Example Code](https://github.com/FetchServe/Rate/wiki/Powershell-Example-Code)
- [Python Example Code](https://github.com/FetchServe/Rate/wiki/Python-Example-Code)
- [Rust Example Code](https://github.com/FetchServe/Rate/wiki/Rust-Example-Code)
- [Shell Example Code](https://github.com/FetchServe/Rate/wiki/Shell-Example-Code)
- [TypeScript Example Code](https://github.com/FetchServe/Rate/wiki/Typescript-Example-Code)

Each of these links will take you to the corresponding wiki page, where you'll find detailed instructions and examples for using the API in your preferred language.

If you'd like to contribute or have any questions, feel free to check the [Issues](https://github.com/FetchServe/Rate/issues) section.

