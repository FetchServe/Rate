# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-20 22:52:13 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2239` | `0.2267` | `0.2148` | `+2.51%` |
| `ALGO-USDT` | `0.1136` | `0.1144` | `0.1085` | `+3.36%` |
| `ATOM-USDT` | `1.7539` | `1.792` | `1.71` | `+0.80%` |
| `AVAX-USDT` | `9.793` | `9.918` | `9.391` | `+1.89%` |
| `BCH-USDT` | `283.54` | `284.17` | `272.32` | `+1.37%` |
| `BTC-USDT` | `83049.7` | `83440.7` | `81205.2` | `+1.19%` |
| `CAKE-USDT` | `2.232` | `2.24` | `2.155` | `+1.40%` |
| `DASH-USDT` | `50.67` | `51.88` | `48.91` | `+0.83%` |
| `DGB-USDT` | `0.003381` | `0.003542` | `0.00327` | `+0.44%` |
| `DOGE-USDT` | `0.0821` | `0.08224` | `0.0785` | `+2.93%` |
| `DOT-USDT` | `1.153` | `1.1877` | `1.126` | `+0.55%` |
| `ETC-USDT` | `7.9421` | `8.0026` | `7.6665` | `+2.05%` |
| `ETH-USDT` | `2457.22` | `2477.89` | `2372.87` | `+2.06%` |
| `LINK-USDT` | `12.3247` | `12.4707` | `11.8381` | `+2.54%` |
| `LTC-USDT` | `61.42` | `61.47` | `58.29` | `+3.03%` |
| `QTUM-USDT` | `0.875` | `0.879` | `0.85` | `+2.21%` |
| `SHIB-USDT` | `0.000005152` | `0.000005155` | `0.000004946` | `+2.77%` |
| `SOL-USDT` | `106.96` | `108.23` | `103.66` | `+1.71%` |
| `TRX-USDT` | `0.3314` | `0.3328` | `0.3306` | `-0.06%` |
| `UNI-USDT` | `7.4901` | `7.5822` | `7.0964` | `+2.72%` |
| `XLM-USDT` | `0.1823` | `0.1826` | `0.175` | `+2.58%` |
| `XMR-USDT` | `622.34` | `627.4` | `597.41` | `+3.13%` |
| `XRP-USDT` | `1.33784` | `1.3462` | `1.28593` | `+2.46%` |

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
    "lastUpdated": "2026-10-20 22:52:13 UTC"
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

