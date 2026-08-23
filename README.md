# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-23 12:24:23 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.225` | `0.2341` | `0.2133` | `-0.83%` |
| `ALGO-USDT` | `0.0932` | `0.0949` | `0.0879` | `-1.27%` |
| `ATOM-USDT` | `1.5783` | `1.6063` | `1.5194` | `-0.26%` |
| `AVAX-USDT` | `7.532` | `7.631` | `7.276` | `-0.59%` |
| `BCH-USDT` | `274.49` | `283.38` | `262.91` | `-1.27%` |
| `BTC-USDT` | `77117.8` | `77546.7` | `75558` | `-0.18%` |
| `CAKE-USDT` | `1.725` | `1.731` | `1.656` | `+0.34%` |
| `DASH-USDT` | `41.25` | `44.44` | `38.42` | `+1.60%` |
| `DGB-USDT` | `0.005067` | `0.0057` | `0.004092` | `+21.27%` |
| `DOGE-USDT` | `0.09242` | `0.09535` | `0.08875` | `+1.44%` |
| `DOT-USDT` | `0.9203` | `0.9391` | `0.8765` | `-1.26%` |
| `ETC-USDT` | `7.8209` | `8.0267` | `7.6278` | `-2.47%` |
| `ETH-USDT` | `2424.16` | `2444.32` | `2356.33` | `-0.42%` |
| `LINK-USDT` | `11.3697` | `11.8962` | `11.0251` | `-4.05%` |
| `LTC-USDT` | `52.29` | `53.71` | `50.6` | `+1.19%` |
| `QTUM-USDT` | `0.865` | `0.871` | `0.805` | `+2.24%` |
| `RVN-USDT` | `0.00329` | `0.00347` | `0.00316` | `-5.18%` |
| `SHIB-USDT` | `0.000005465` | `0.000005579` | `0.000005199` | `-1.46%` |
| `SOL-USDT` | `94.55` | `97.28` | `91.58` | `+0.39%` |
| `TRX-USDT` | `0.3437` | `0.3457` | `0.3419` | `+0.14%` |
| `UNI-USDT` | `4.2955` | `4.3779` | `4.0129` | `+1.91%` |
| `XLM-USDT` | `0.1965` | `0.2022` | `0.1878` | `-2.67%` |
| `XMR-USDT` | `427.91` | `442.74` | `412.87` | `-0.47%` |
| `XRP-USDT` | `1.49206` | `1.52511` | `1.42955` | `-1.93%` |

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
    "lastUpdated": "2026-08-23 12:24:23 UTC"
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

