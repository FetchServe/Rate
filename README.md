# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-13 17:00:20 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2075` | `0.2085` | `0.2033` | `-0.33%` |
| `ALGO-USDT` | `0.0944` | `0.0944` | `0.0916` | `+0.31%` |
| `ATOM-USDT` | `1.6056` | `1.636` | `1.5714` | `-1.74%` |
| `AVAX-USDT` | `7.397` | `7.462` | `7.281` | `-0.05%` |
| `BCH-USDT` | `224.96` | `230.16` | `222` | `-1.66%` |
| `BTC-USDT` | `77277.8` | `77390.1` | `76500` | `-0.11%` |
| `CAKE-USDT` | `2.204` | `2.23` | `2.163` | `-0.63%` |
| `DASH-USDT` | `54.05` | `56.12` | `53.25` | `-3.39%` |
| `DGB-USDT` | `0.0045` | `0.004693` | `0.004498` | `-3.39%` |
| `DOGE-USDT` | `0.08397` | `0.08518` | `0.08289` | `-1.23%` |
| `DOT-USDT` | `1.0183` | `1.0435` | `0.9964` | `-1.99%` |
| `ETC-USDT` | `7.6395` | `7.7187` | `7.4761` | `-1.02%` |
| `ETH-USDT` | `2505` | `2534.42` | `2462.33` | `-1.04%` |
| `LINK-USDT` | `11.3596` | `11.6817` | `11.1982` | `-1.52%` |
| `LTC-USDT` | `54.72` | `57.14` | `53.26` | `+1.46%` |
| `QTUM-USDT` | `0.954` | `0.999` | `0.908` | `+4.26%` |
| `RVN-USDT` | `0.00238` | `0.00238` | `0.00228` | `+3.03%` |
| `SHIB-USDT` | `0.000005228` | `0.000005321` | `0.000005173` | `-1.04%` |
| `SOL-USDT` | `100.81` | `102.33` | `99.43` | `-1.24%` |
| `TRX-USDT` | `0.3412` | `0.3418` | `0.3393` | `+0.23%` |
| `UNI-USDT` | `6.3046` | `6.4864` | `6.1567` | `-1.18%` |
| `XLM-USDT` | `0.1789` | `0.182` | `0.1772` | `-1.59%` |
| `XMR-USDT` | `537.43` | `544.51` | `526.23` | `+1.97%` |
| `XRP-USDT` | `1.35139` | `1.38351` | `1.33301` | `-1.33%` |

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
    "lastUpdated": "2026-09-13 17:00:20 UTC"
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

