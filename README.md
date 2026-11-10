# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-10 00:47:00 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1773` | `0.1834` | `0.1713` | `+0.68%` |
| `ALGO-USDT` | `0.0925` | `0.0956` | `0.0894` | `+0.76%` |
| `ATOM-USDT` | `1.372` | `1.4016` | `1.2986` | `+4.30%` |
| `AVAX-USDT` | `8.707` | `9.02` | `7.815` | `+9.06%` |
| `BCH-USDT` | `238.59` | `245.01` | `235.83` | `-0.96%` |
| `BTC-USDT` | `75050` | `75586.6` | `73738.3` | `+0.04%` |
| `CAKE-USDT` | `1.863` | `1.903` | `1.822` | `+0.32%` |
| `DASH-USDT` | `47.12` | `48.13` | `45.44` | `+3.06%` |
| `DGB-USDT` | `0.003061` | `0.00322` | `0.003051` | `-3.65%` |
| `DOGE-USDT` | `0.06992` | `0.07089` | `0.06794` | `+0.90%` |
| `DOT-USDT` | `0.8563` | `0.8934` | `0.8497` | `-1.39%` |
| `ETC-USDT` | `6.7915` | `6.9912` | `6.5934` | `+1.66%` |
| `ETH-USDT` | `2127.35` | `2160.31` | `2083.24` | `-0.46%` |
| `LINK-USDT` | `10.6457` | `10.8283` | `10.2142` | `+1.40%` |
| `LTC-USDT` | `51.43` | `52.29` | `49.79` | `+1.62%` |
| `QTUM-USDT` | `0.692` | `0.704` | `0.665` | `+1.76%` |
| `SHIB-USDT` | `0.000004431` | `0.000004516` | `0.000004311` | `+0.77%` |
| `SOL-USDT` | `86.52` | `88.45` | `85.15` | `-0.59%` |
| `TRX-USDT` | `0.3179` | `0.3195` | `0.3162` | `-0.40%` |
| `UNI-USDT` | `7.0017` | `7.1084` | `6.6464` | `+1.68%` |
| `XLM-USDT` | `0.1472` | `0.1501` | `0.144` | `+0.00%` |
| `XMR-USDT` | `583.79` | `605.6` | `582.22` | `-2.96%` |
| `XRP-USDT` | `1.10076` | `1.12638` | `1.07656` | `-1.85%` |

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
    "lastUpdated": "2026-11-10 00:47:00 UTC"
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

