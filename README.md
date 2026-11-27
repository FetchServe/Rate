# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-27 00:12:48 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1486` | `0.1513` | `0.1459` | `+1.57%` |
| `ALGO-USDT` | `0.0818` | `0.0824` | `0.078` | `+4.33%` |
| `ATOM-USDT` | `1.215` | `1.2579` | `1.1755` | `-1.59%` |
| `AVAX-USDT` | `6.59` | `6.748` | `6.47` | `-0.97%` |
| `BCH-USDT` | `210.25` | `211.6` | `204.32` | `+1.57%` |
| `BTC-USDT` | `60499.6` | `61615.2` | `59917.4` | `-0.24%` |
| `CAKE-USDT` | `1.567` | `1.588` | `1.551` | `+0.19%` |
| `DASH-USDT` | `36.06` | `36.91` | `34.94` | `-0.05%` |
| `DGB-USDT` | `0.002525` | `0.00258` | `0.002494` | `+0.35%` |
| `DOGE-USDT` | `0.05644` | `0.05727` | `0.05582` | `+0.19%` |
| `DOT-USDT` | `0.674` | `0.6791` | `0.6562` | `+1.73%` |
| `ETC-USDT` | `5.9143` | `5.9969` | `5.8332` | `+0.19%` |
| `ETH-USDT` | `1689.01` | `1729.75` | `1668.07` | `-0.39%` |
| `LINK-USDT` | `9.2992` | `9.425` | `9.0403` | `+2.10%` |
| `LTC-USDT` | `43.83` | `44.28` | `42.87` | `+1.76%` |
| `QTUM-USDT` | `0.636` | `0.644` | `0.632` | `-0.31%` |
| `SHIB-USDT` | `0.000003624` | `0.000003672` | `0.000003595` | `+0.47%` |
| `SOL-USDT` | `71.01` | `71.9` | `69.79` | `+0.33%` |
| `TRX-USDT` | `0.3039` | `0.3051` | `0.3018` | `+0.03%` |
| `UNI-USDT` | `4.6621` | `4.8541` | `4.5402` | `-2.50%` |
| `XLM-USDT` | `0.1266` | `0.1307` | `0.1254` | `-1.63%` |
| `XMR-USDT` | `453.51` | `529.3` | `428.1` | `-11.58%` |
| `XRP-USDT` | `0.9426` | `0.96379` | `0.93384` | `+0.19%` |

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
    "lastUpdated": "2026-11-27 00:12:48 UTC"
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

