# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-15 20:20:06 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1967` | `0.2158` | `0.193` | `-8.51%` |
| `ALGO-USDT` | `0.0895` | `0.0984` | `0.0888` | `-8.76%` |
| `ATOM-USDT` | `1.5213` | `1.6104` | `1.5` | `-5.25%` |
| `AVAX-USDT` | `7.299` | `7.803` | `7.191` | `-5.62%` |
| `BCH-USDT` | `216.76` | `231.3` | `212.98` | `-5.77%` |
| `BTC-USDT` | `75941.8` | `79592.3` | `74973.8` | `-4.33%` |
| `CAKE-USDT` | `2.231` | `2.398` | `2.202` | `-6.61%` |
| `DASH-USDT` | `50.65` | `56.39` | `49.6` | `-8.47%` |
| `DGB-USDT` | `0.003728` | `0.004503` | `0.00369` | `-15.25%` |
| `DOGE-USDT` | `0.08034` | `0.08613` | `0.07846` | `-6.39%` |
| `DOT-USDT` | `0.9517` | `1.0377` | `0.9339` | `-7.95%` |
| `ETC-USDT` | `7.2324` | `7.7616` | `7.0913` | `-6.44%` |
| `ETH-USDT` | `2403.63` | `2614.25` | `2358.8` | `-7.29%` |
| `LINK-USDT` | `11.0255` | `11.9648` | `10.7897` | `-7.45%` |
| `LTC-USDT` | `51.45` | `54.47` | `50.77` | `-5.17%` |
| `QTUM-USDT` | `0.87` | `0.942` | `0.844` | `-6.65%` |
| `RVN-USDT` | `0.00221` | `0.00238` | `0.00221` | `-7.14%` |
| `SHIB-USDT` | `0.000004965` | `0.000005391` | `0.000004914` | `-7.43%` |
| `SOL-USDT` | `97.38` | `104.82` | `95.81` | `-6.81%` |
| `TRX-USDT` | `0.3323` | `0.341` | `0.3317` | `-2.46%` |
| `UNI-USDT` | `6.3878` | `6.835` | `6.1667` | `-5.72%` |
| `XLM-USDT` | `0.1765` | `0.1986` | `0.1759` | `-9.67%` |
| `XMR-USDT` | `496.36` | `520` | `495.63` | `-3.66%` |
| `XRP-USDT` | `1.28026` | `1.49113` | `1.2775` | `-13.89%` |

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
    "lastUpdated": "2026-09-15 20:20:06 UTC"
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

