# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-16 10:15:39 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1766` | `0.1793` | `0.1756` | `-1.34%` |
| `ALGO-USDT` | `0.0791` | `0.0803` | `0.0787` | `-0.50%` |
| `ATOM-USDT` | `1.4973` | `1.5041` | `1.4638` | `+0.55%` |
| `AVAX-USDT` | `6.353` | `6.598` | `6.223` | `-3.52%` |
| `BCH-USDT` | `203.95` | `206.97` | `202.86` | `-0.59%` |
| `BTC-USDT` | `62980.7` | `63163.5` | `62943.8` | `-0.05%` |
| `CAKE-USDT` | `1.451` | `1.454` | `1.424` | `+1.61%` |
| `DASH-USDT` | `29.62` | `30.23` | `29.49` | `-1.26%` |
| `DGB-USDT` | `0.004065` | `0.0041` | `0.0039` | `+2.39%` |
| `DOGE-USDT` | `0.06972` | `0.07013` | `0.06952` | `-0.45%` |
| `DOT-USDT` | `0.7597` | `0.7842` | `0.756` | `-2.90%` |
| `ETC-USDT` | `6.1744` | `6.2812` | `6.159` | `-1.61%` |
| `ETH-USDT` | `1879.68` | `1886.39` | `1877.12` | `+0.03%` |
| `LINK-USDT` | `9.4086` | `9.6315` | `9.2778` | `+0.66%` |
| `LTC-USDT` | `44.38` | `44.44` | `43.97` | `+0.72%` |
| `QTUM-USDT` | `0.673` | `0.679` | `0.67` | `-0.59%` |
| `RVN-USDT` | `0.00272` | `0.00286` | `0.00262` | `+3.42%` |
| `SHIB-USDT` | `0.000004462` | `0.000004598` | `0.000004462` | `-2.59%` |
| `SOL-USDT` | `75.21` | `75.72` | `75.2` | `-0.10%` |
| `TRX-USDT` | `0.3314` | `0.3326` | `0.3308` | `-0.27%` |
| `UNI-USDT` | `3.2712` | `3.3025` | `3.2174` | `+0.35%` |
| `XLM-USDT` | `0.1569` | `0.1598` | `0.1566` | `-0.94%` |
| `XMR-USDT` | `409` | `414.24` | `400.27` | `+0.95%` |
| `XRP-USDT` | `0.99829` | `1.0065` | `0.99822` | `-0.47%` |

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
    "lastUpdated": "2026-08-16 10:15:39 UTC"
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

