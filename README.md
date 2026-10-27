# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-27 01:51:49 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2051` | `0.2081` | `0.2006` | `+1.93%` |
| `ALGO-USDT` | `0.105` | `0.1062` | `0.1027` | `+1.54%` |
| `ATOM-USDT` | `1.6287` | `1.6685` | `1.616` | `+0.63%` |
| `AVAX-USDT` | `8.908` | `9.058` | `8.764` | `+0.97%` |
| `BCH-USDT` | `283.17` | `284.61` | `273.94` | `+2.39%` |
| `BTC-USDT` | `80100.7` | `80809.5` | `79385.1` | `+0.59%` |
| `CAKE-USDT` | `2.144` | `2.164` | `2.054` | `+3.97%` |
| `DASH-USDT` | `54.11` | `54.38` | `50.08` | `+6.76%` |
| `DGB-USDT` | `0.003417` | `0.003529` | `0.003244` | `+4.75%` |
| `DOGE-USDT` | `0.07777` | `0.07826` | `0.076` | `+1.80%` |
| `DOT-USDT` | `0.9988` | `1.0353` | `0.9975` | `-1.56%` |
| `ETC-USDT` | `7.6038` | `7.6665` | `7.404` | `+2.62%` |
| `ETH-USDT` | `2321.25` | `2344.72` | `2293.06` | `+0.53%` |
| `LINK-USDT` | `11.3306` | `11.6247` | `11.2544` | `-0.01%` |
| `LTC-USDT` | `56.64` | `57.26` | `55.99` | `+0.49%` |
| `QTUM-USDT` | `0.821` | `0.903` | `0.813` | `+0.98%` |
| `SHIB-USDT` | `0.000004872` | `0.000004916` | `0.00000479` | `+1.35%` |
| `SOL-USDT` | `100.61` | `102.72` | `99.89` | `-0.11%` |
| `TRX-USDT` | `0.3298` | `0.3317` | `0.3293` | `-0.03%` |
| `UNI-USDT` | `7.1117` | `7.2101` | `6.7807` | `+3.92%` |
| `XLM-USDT` | `0.1692` | `0.1711` | `0.1666` | `+1.25%` |
| `XMR-USDT` | `609.86` | `611.89` | `582.92` | `+3.55%` |
| `XRP-USDT` | `1.30418` | `1.3133` | `1.27321` | `+1.48%` |

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
    "lastUpdated": "2026-10-27 01:51:49 UTC"
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

