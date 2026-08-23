# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-23 11:14:41 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.222` | `0.2341` | `0.2133` | `-0.40%` |
| `ALGO-USDT` | `0.0922` | `0.0949` | `0.0879` | `-0.86%` |
| `ATOM-USDT` | `1.5647` | `1.6063` | `1.5194` | `-0.05%` |
| `AVAX-USDT` | `7.447` | `7.631` | `7.276` | `-0.68%` |
| `BCH-USDT` | `272.86` | `283.38` | `262.91` | `-0.92%` |
| `BTC-USDT` | `76866.3` | `77546.7` | `75558` | `-0.02%` |
| `CAKE-USDT` | `1.714` | `1.725` | `1.656` | `+0.88%` |
| `DASH-USDT` | `40.98` | `44.44` | `38.42` | `+2.45%` |
| `DGB-USDT` | `0.004974` | `0.00503` | `0.004092` | `+20.37%` |
| `DOGE-USDT` | `0.09218` | `0.09535` | `0.08875` | `+2.63%` |
| `DOT-USDT` | `0.9107` | `0.9391` | `0.8765` | `-0.77%` |
| `ETC-USDT` | `7.8283` | `8.0267` | `7.6278` | `-1.36%` |
| `ETH-USDT` | `2420.05` | `2444.32` | `2356.33` | `+0.47%` |
| `LINK-USDT` | `11.3149` | `11.8962` | `11.0251` | `-2.17%` |
| `LTC-USDT` | `52.2` | `53.71` | `50.6` | `+1.97%` |
| `QTUM-USDT` | `0.858` | `0.871` | `0.805` | `+1.53%` |
| `RVN-USDT` | `0.00327` | `0.00347` | `0.00316` | `-4.66%` |
| `SHIB-USDT` | `0.000005387` | `0.000005579` | `0.000005199` | `-1.33%` |
| `SOL-USDT` | `93.86` | `97.28` | `91.58` | `+1.07%` |
| `TRX-USDT` | `0.3438` | `0.3457` | `0.3419` | `+0.43%` |
| `UNI-USDT` | `4.264` | `4.3779` | `4.0129` | `+4.41%` |
| `XLM-USDT` | `0.1938` | `0.2022` | `0.1878` | `-2.17%` |
| `XMR-USDT` | `431.38` | `442.74` | `412.87` | `+1.38%` |
| `XRP-USDT` | `1.48158` | `1.52991` | `1.42955` | `-0.36%` |

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
    "lastUpdated": "2026-08-23 11:14:41 UTC"
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

