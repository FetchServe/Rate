# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-05 08:50:04 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1991` | `0.2016` | `0.1889` | `+3.64%` |
| `ALGO-USDT` | `0.1005` | `0.101` | `0.0942` | `+6.01%` |
| `ATOM-USDT` | `1.5258` | `1.5381` | `1.417` | `+6.87%` |
| `AVAX-USDT` | `8.784` | `9.159` | `8.618` | `+1.05%` |
| `BCH-USDT` | `289.7` | `289.7` | `272.26` | `+4.66%` |
| `BTC-USDT` | `80511.8` | `81199.2` | `78010.6` | `+2.58%` |
| `CAKE-USDT` | `2.024` | `2.044` | `1.906` | `+5.36%` |
| `DASH-USDT` | `48.84` | `49.96` | `46.45` | `+2.84%` |
| `DGB-USDT` | `0.003128` | `0.003632` | `0.003055` | `-0.50%` |
| `DOGE-USDT` | `0.07705` | `0.07837` | `0.07441` | `+2.28%` |
| `DOT-USDT` | `0.9582` | `0.9954` | `0.937` | `+0.20%` |
| `ETC-USDT` | `7.471` | `7.471` | `7.0806` | `+4.66%` |
| `ETH-USDT` | `2420.39` | `2449.7` | `2310.08` | `+4.01%` |
| `LINK-USDT` | `11.6184` | `11.7965` | `11.0515` | `+3.82%` |
| `LTC-USDT` | `56.29` | `57.04` | `54.46` | `+2.88%` |
| `QTUM-USDT` | `0.757` | `0.77` | `0.734` | `-0.13%` |
| `SHIB-USDT` | `0.000004752` | `0.000004853` | `0.000004634` | `+1.27%` |
| `SOL-USDT` | `96.58` | `98.15` | `92.47` | `+3.41%` |
| `TRX-USDT` | `0.3185` | `0.323` | `0.3178` | `-1.20%` |
| `UNI-USDT` | `7.6437` | `7.8193` | `7.256` | `+2.27%` |
| `XLM-USDT` | `0.1677` | `0.1711` | `0.1621` | `+2.38%` |
| `XMR-USDT` | `636.33` | `648` | `624.65` | `-0.98%` |
| `XRP-USDT` | `1.3218` | `1.34173` | `1.27656` | `+3.11%` |

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
    "lastUpdated": "2026-11-05 08:50:04 UTC"
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

