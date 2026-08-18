# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-18 21:45:30 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1731` | `0.1769` | `0.1713` | `-0.68%` |
| `ALGO-USDT` | `0.0775` | `0.0789` | `0.0767` | `-1.27%` |
| `ATOM-USDT` | `1.417` | `1.4799` | `1.3781` | `-0.16%` |
| `AVAX-USDT` | `6.307` | `6.455` | `6.237` | `-0.63%` |
| `BCH-USDT` | `203.61` | `205.5` | `202.62` | `-0.57%` |
| `BTC-USDT` | `64583` | `65050` | `64025.8` | `+0.37%` |
| `CAKE-USDT` | `1.506` | `1.526` | `1.453` | `+2.72%` |
| `DASH-USDT` | `29.77` | `30.63` | `29.75` | `-2.36%` |
| `DGB-USDT` | `0.003922` | `0.004167` | `0.003802` | `-2.34%` |
| `DOGE-USDT` | `0.07016` | `0.07055` | `0.0696` | `-0.36%` |
| `DOT-USDT` | `0.7492` | `0.763` | `0.7237` | `-1.60%` |
| `ETC-USDT` | `6.075` | `6.1957` | `6.0224` | `-1.94%` |
| `ETH-USDT` | `1911.7` | `1922.71` | `1885.75` | `+0.28%` |
| `LINK-USDT` | `9.5193` | `9.5586` | `9.3345` | `+0.08%` |
| `LTC-USDT` | `44.47` | `44.75` | `44.15` | `-0.29%` |
| `QTUM-USDT` | `0.681` | `0.696` | `0.674` | `-0.29%` |
| `RVN-USDT` | `0.00272` | `0.00281` | `0.00269` | `-3.20%` |
| `SHIB-USDT` | `0.000004386` | `0.000004492` | `0.000004361` | `-2.27%` |
| `SOL-USDT` | `76.92` | `77.4` | `75.22` | `+1.29%` |
| `TRX-USDT` | `0.333` | `0.3396` | `0.3309` | `+0.48%` |
| `UNI-USDT` | `3.3102` | `3.3126` | `3.2303` | `+0.67%` |
| `XLM-USDT` | `0.154` | `0.1583` | `0.1525` | `-2.22%` |
| `XMR-USDT` | `413.7` | `422.34` | `409` | `-0.57%` |
| `XRP-USDT` | `1.00092` | `1.00647` | `0.98911` | `-0.18%` |

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
    "lastUpdated": "2026-08-18 21:45:30 UTC"
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

