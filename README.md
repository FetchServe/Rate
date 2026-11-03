# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-03 19:56:51 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1899` | `0.1926` | `0.1855` | `+1.38%` |
| `ALGO-USDT` | `0.0944` | `0.0949` | `0.0905` | `+4.19%` |
| `ATOM-USDT` | `1.4133` | `1.4513` | `1.3954` | `-0.14%` |
| `AVAX-USDT` | `8.586` | `8.692` | `8.29` | `+3.24%` |
| `BCH-USDT` | `274.01` | `279.38` | `272` | `-0.86%` |
| `BTC-USDT` | `77527.5` | `77882` | `76396` | `+0.84%` |
| `CAKE-USDT` | `1.867` | `1.877` | `1.82` | `+0.91%` |
| `DASH-USDT` | `46.02` | `46.83` | `45.42` | `+0.28%` |
| `DGB-USDT` | `0.003107` | `0.003176` | `0.00305` | `-1.52%` |
| `DOGE-USDT` | `0.07507` | `0.07563` | `0.07349` | `+2.14%` |
| `DOT-USDT` | `0.9434` | `0.9501` | `0.9271` | `+1.10%` |
| `ETC-USDT` | `7.0573` | `7.0853` | `6.8846` | `+2.01%` |
| `ETH-USDT` | `2285.41` | `2308` | `2241.01` | `+1.75%` |
| `LINK-USDT` | `11.0442` | `11.3086` | `11.0115` | `-0.03%` |
| `LTC-USDT` | `54.12` | `55.16` | `53.5` | `+0.61%` |
| `QTUM-USDT` | `0.746` | `0.768` | `0.732` | `+1.22%` |
| `SHIB-USDT` | `0.000004619` | `0.000004657` | `0.000004531` | `+1.87%` |
| `SOL-USDT` | `93.19` | `93.93` | `91.11` | `+2.10%` |
| `TRX-USDT` | `0.3243` | `0.3243` | `0.3172` | `+2.14%` |
| `UNI-USDT` | `7.2072` | `7.4038` | `6.8089` | `+2.91%` |
| `XLM-USDT` | `0.1629` | `0.167` | `0.1606` | `-0.54%` |
| `XMR-USDT` | `632.22` | `638.21` | `603.9` | `+4.62%` |
| `XRP-USDT` | `1.27551` | `1.29114` | `1.24461` | `+2.20%` |

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
    "lastUpdated": "2026-11-03 19:56:51 UTC"
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

