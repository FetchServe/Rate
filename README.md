# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-06 18:10:16 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1875` | `0.1897` | `0.1778` | `+3.41%` |
| `ALGO-USDT` | `0.0974` | `0.0987` | `0.0909` | `+3.17%` |
| `ATOM-USDT` | `1.4209` | `1.4521` | `1.3504` | `+0.90%` |
| `AVAX-USDT` | `8.403` | `8.472` | `8.084` | `+2.27%` |
| `BCH-USDT` | `267.27` | `279.13` | `261.45` | `-1.79%` |
| `BTC-USDT` | `75761.6` | `76555.2` | `74893.7` | `-0.09%` |
| `CAKE-USDT` | `1.92` | `1.948` | `1.881` | `+1.21%` |
| `DASH-USDT` | `47.78` | `48.7` | `43.83` | `+8.36%` |
| `DGB-USDT` | `0.003022` | `0.003206` | `0.002933` | `+2.64%` |
| `DOGE-USDT` | `0.07287` | `0.07339` | `0.07021` | `+2.03%` |
| `DOT-USDT` | `0.9271` | `0.9489` | `0.8947` | `+2.15%` |
| `ETC-USDT` | `7.0657` | `7.1476` | `6.7915` | `+2.77%` |
| `ETH-USDT` | `2226.29` | `2269.66` | `2206.31` | `-1.01%` |
| `LINK-USDT` | `10.8686` | `11.038` | `10.51` | `+2.00%` |
| `LTC-USDT` | `52.97` | `53.51` | `51.08` | `+2.71%` |
| `QTUM-USDT` | `0.735` | `0.742` | `0.709` | `+3.23%` |
| `SHIB-USDT` | `0.000004585` | `0.000004625` | `0.000004457` | `+1.70%` |
| `SOL-USDT` | `90.07` | `91.59` | `88.3` | `+1.13%` |
| `TRX-USDT` | `0.3193` | `0.3252` | `0.317` | `+0.69%` |
| `UNI-USDT` | `6.9144` | `7.1298` | `6.7189` | `+1.20%` |
| `XLM-USDT` | `0.1553` | `0.1576` | `0.1516` | `+1.83%` |
| `XMR-USDT` | `621.44` | `625.38` | `606.08` | `+1.29%` |
| `XRP-USDT` | `1.18558` | `1.24553` | `1.1745` | `-3.75%` |

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
    "lastUpdated": "2026-11-06 18:10:16 UTC"
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

