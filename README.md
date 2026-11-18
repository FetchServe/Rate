# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-18 01:05:26 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1539` | `0.1565` | `0.1493` | `+1.18%` |
| `ALGO-USDT` | `0.0794` | `0.0809` | `0.0773` | `+0.37%` |
| `ATOM-USDT` | `1.3219` | `1.3795` | `1.2995` | `+0.05%` |
| `AVAX-USDT` | `7.238` | `7.314` | `6.959` | `+2.15%` |
| `BCH-USDT` | `210.64` | `213.75` | `204.58` | `+1.37%` |
| `BTC-USDT` | `64620.6` | `65437.6` | `63352` | `-0.09%` |
| `CAKE-USDT` | `1.645` | `1.662` | `1.597` | `+1.66%` |
| `DASH-USDT` | `38.32` | `38.95` | `36.99` | `+2.73%` |
| `DGB-USDT` | `0.002735` | `0.003035` | `0.002608` | `+4.86%` |
| `DOGE-USDT` | `0.05959` | `0.06044` | `0.05742` | `+1.20%` |
| `DOT-USDT` | `0.7372` | `0.7479` | `0.7131` | `+1.19%` |
| `ETC-USDT` | `5.9742` | `6.039` | `5.7613` | `+2.14%` |
| `ETH-USDT` | `1816.18` | `1843.45` | `1751.41` | `+0.01%` |
| `LINK-USDT` | `9.2394` | `9.4103` | `8.9394` | `+1.64%` |
| `LTC-USDT` | `44.73` | `45.43` | `43.73` | `+0.60%` |
| `QTUM-USDT` | `0.67` | `0.67` | `0.647` | `+3.55%` |
| `SHIB-USDT` | `0.000003864` | `0.000003911` | `0.000003748` | `+0.49%` |
| `SOL-USDT` | `74.77` | `75.77` | `71.07` | `+4.47%` |
| `TRX-USDT` | `0.3082` | `0.3087` | `0.3048` | `+0.88%` |
| `UNI-USDT` | `5.2446` | `5.456` | `5.1143` | `+2.03%` |
| `XLM-USDT` | `0.1408` | `0.142` | `0.1358` | `+2.62%` |
| `XMR-USDT` | `510.23` | `524` | `490.43` | `+3.59%` |
| `XRP-USDT` | `0.9765` | `0.99137` | `0.94548` | `+2.34%` |

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
    "lastUpdated": "2026-11-18 01:05:26 UTC"
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

