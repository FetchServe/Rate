# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-12 10:03:46 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2515` | `0.2563` | `0.2452` | `+1.78%` |
| `ALGO-USDT` | `0.1299` | `0.1336` | `0.1177` | `+8.88%` |
| `ATOM-USDT` | `1.8776` | `2.0527` | `1.85` | `-2.42%` |
| `AVAX-USDT` | `11.043` | `11.111` | `10.318` | `+6.91%` |
| `BCH-USDT` | `283.74` | `288.85` | `277.07` | `+1.93%` |
| `BTC-USDT` | `83538.3` | `84334.1` | `82971.5` | `+0.60%` |
| `CAKE-USDT` | `2.378` | `2.432` | `2.236` | `+5.22%` |
| `DASH-USDT` | `52.37` | `54.45` | `50.79` | `+2.70%` |
| `DGB-USDT` | `0.003472` | `0.003825` | `0.003447` | `-1.64%` |
| `DOGE-USDT` | `0.08707` | `0.08812` | `0.08504` | `+2.00%` |
| `DOT-USDT` | `1.2485` | `1.2834` | `1.2248` | `+0.83%` |
| `ETC-USDT` | `8.445` | `8.5576` | `8.2966` | `+1.29%` |
| `ETH-USDT` | `2558.65` | `2579.24` | `2498.1` | `+2.23%` |
| `LINK-USDT` | `13.3618` | `13.5034` | `12.8417` | `+3.72%` |
| `LTC-USDT` | `65.1` | `65.86` | `63.4` | `+2.21%` |
| `QTUM-USDT` | `0.979` | `1.028` | `0.979` | `-1.90%` |
| `SHIB-USDT` | `0.000005458` | `0.000005555` | `0.000005383` | `+1.18%` |
| `SOL-USDT` | `111.69` | `113.38` | `109.25` | `+1.99%` |
| `TRX-USDT` | `0.3317` | `0.3331` | `0.33` | `+0.36%` |
| `UNI-USDT` | `7.5988` | `7.8995` | `7.5134` | `+0.43%` |
| `XLM-USDT` | `0.2012` | `0.206` | `0.1962` | `+1.61%` |
| `XMR-USDT` | `531.24` | `545.72` | `529.36` | `+0.03%` |
| `XRP-USDT` | `1.40529` | `1.4263` | `1.38901` | `+0.89%` |

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
    "lastUpdated": "2026-10-12 10:03:46 UTC"
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

