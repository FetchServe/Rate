# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-19 00:19:18 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2202` | `0.2222` | `0.2111` | `+0.00%` |
| `ALGO-USDT` | `0.1109` | `0.1131` | `0.1059` | `-0.98%` |
| `ATOM-USDT` | `1.6895` | `1.7231` | `1.6237` | `-0.76%` |
| `AVAX-USDT` | `9.706` | `9.899` | `9.261` | `-0.66%` |
| `BCH-USDT` | `276.16` | `278.09` | `264.41` | `+0.14%` |
| `BTC-USDT` | `82046.8` | `82281.1` | `80690.5` | `+0.69%` |
| `CAKE-USDT` | `2.185` | `2.208` | `2.106` | `-0.41%` |
| `DASH-USDT` | `48.78` | `49.59` | `46.25` | `+0.47%` |
| `DGB-USDT` | `0.003457` | `0.00378` | `0.00338` | `+0.43%` |
| `DOGE-USDT` | `0.07918` | `0.08002` | `0.07609` | `-0.12%` |
| `DOT-USDT` | `1.1085` | `1.1218` | `1.0469` | `-0.26%` |
| `ETC-USDT` | `7.7548` | `7.8335` | `7.4339` | `-0.44%` |
| `ETH-USDT` | `2404.84` | `2429.83` | `2329.43` | `+0.15%` |
| `LINK-USDT` | `12.0245` | `12.0923` | `11.5368` | `+0.38%` |
| `LTC-USDT` | `59.06` | `60.03` | `56.7` | `+0.47%` |
| `QTUM-USDT` | `0.856` | `0.88` | `0.825` | `-2.28%` |
| `SHIB-USDT` | `0.000004988` | `0.000005005` | `0.000004801` | `+0.14%` |
| `SOL-USDT` | `103.8` | `104.78` | `100.44` | `+0.46%` |
| `TRX-USDT` | `0.3322` | `0.3344` | `0.3316` | `-0.44%` |
| `UNI-USDT` | `7.1488` | `7.3538` | `6.813` | `-0.50%` |
| `XLM-USDT` | `0.1776` | `0.1788` | `0.1718` | `+0.33%` |
| `XMR-USDT` | `596.89` | `609.55` | `571.84` | `+3.04%` |
| `XRP-USDT` | `1.30231` | `1.31009` | `1.25603` | `+0.65%` |

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
    "lastUpdated": "2026-10-19 00:19:18 UTC"
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

