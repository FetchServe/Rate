# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-21 01:10:24 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2242` | `0.2267` | `0.2148` | `+3.74%` |
| `ALGO-USDT` | `0.1136` | `0.115` | `0.1085` | `+3.64%` |
| `ATOM-USDT` | `1.7326` | `1.792` | `1.71` | `-0.36%` |
| `AVAX-USDT` | `9.732` | `9.918` | `9.391` | `+2.76%` |
| `BCH-USDT` | `284.25` | `287` | `272.32` | `+2.48%` |
| `BTC-USDT` | `82827.9` | `83440.7` | `81205.2` | `+1.86%` |
| `CAKE-USDT` | `2.225` | `2.24` | `2.155` | `+2.67%` |
| `DASH-USDT` | `50.45` | `51.88` | `48.91` | `+1.79%` |
| `DGB-USDT` | `0.003371` | `0.003542` | `0.003274` | `+0.74%` |
| `DOGE-USDT` | `0.08185` | `0.08233` | `0.0785` | `+3.85%` |
| `DOT-USDT` | `1.1519` | `1.1877` | `1.126` | `+1.59%` |
| `ETC-USDT` | `7.9469` | `8.0026` | `7.6665` | `+3.29%` |
| `ETH-USDT` | `2443.22` | `2477.89` | `2374.43` | `+2.70%` |
| `LINK-USDT` | `12.333` | `12.4707` | `11.8381` | `+3.89%` |
| `LTC-USDT` | `61.55` | `61.9` | `58.29` | `+4.18%` |
| `QTUM-USDT` | `0.877` | `0.879` | `0.85` | `+3.05%` |
| `SHIB-USDT` | `0.000005129` | `0.000005155` | `0.000004946` | `+3.28%` |
| `SOL-USDT` | `106.28` | `108.23` | `103.66` | `+2.12%` |
| `TRX-USDT` | `0.3314` | `0.3328` | `0.3306` | `-0.09%` |
| `UNI-USDT` | `7.5331` | `7.7036` | `7.0964` | `+4.24%` |
| `XLM-USDT` | `0.1819` | `0.1826` | `0.175` | `+3.46%` |
| `XMR-USDT` | `581.53` | `627.4` | `581.21` | `-3.38%` |
| `XRP-USDT` | `1.33424` | `1.3462` | `1.28593` | `+3.46%` |

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
    "lastUpdated": "2026-10-21 01:10:24 UTC"
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

