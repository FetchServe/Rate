# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-22 17:15:57 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1447` | `0.1476` | `0.1409` | `-0.27%` |
| `ALGO-USDT` | `0.0751` | `0.0757` | `0.0731` | `+0.67%` |
| `ATOM-USDT` | `1.1738` | `1.2447` | `1.1396` | `-1.07%` |
| `AVAX-USDT` | `6.678` | `6.773` | `6.48` | `+0.86%` |
| `BCH-USDT` | `198.55` | `200.61` | `194.27` | `+0.23%` |
| `BTC-USDT` | `60808.8` | `61668` | `58771.4` | `+0.90%` |
| `CAKE-USDT` | `1.518` | `1.525` | `1.449` | `+2.29%` |
| `DASH-USDT` | `35.52` | `36.06` | `33.96` | `+3.67%` |
| `DGB-USDT` | `0.002615` | `0.002649` | `0.002469` | `+1.75%` |
| `DOGE-USDT` | `0.05522` | `0.05597` | `0.05377` | `+0.09%` |
| `DOT-USDT` | `0.6645` | `0.6671` | `0.6411` | `+1.21%` |
| `ETC-USDT` | `5.6096` | `5.645` | `5.4156` | `+1.98%` |
| `ETH-USDT` | `1713.81` | `1732.08` | `1648.43` | `+1.63%` |
| `LINK-USDT` | `8.8158` | `8.9099` | `8.4975` | `+2.66%` |
| `LTC-USDT` | `40.02` | `40.31` | `38.91` | `+0.05%` |
| `QTUM-USDT` | `0.616` | `0.622` | `0.606` | `-0.96%` |
| `SHIB-USDT` | `0.000003604` | `0.00000367` | `0.00000356` | `-0.63%` |
| `SOL-USDT` | `70.37` | `71.41` | `68.75` | `-0.62%` |
| `TRX-USDT` | `0.3054` | `0.3068` | `0.3036` | `+0.00%` |
| `UNI-USDT` | `4.714` | `4.7685` | `4.5572` | `-0.31%` |
| `XLM-USDT` | `0.1278` | `0.1304` | `0.1265` | `-0.77%` |
| `XMR-USDT` | `488.8` | `495.32` | `476.47` | `+0.74%` |
| `XRP-USDT` | `0.92722` | `0.9389` | `0.91194` | `-0.45%` |

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
    "lastUpdated": "2026-11-22 17:15:57 UTC"
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

