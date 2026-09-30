# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-30 01:25:48 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2465` | `0.2547` | `0.239` | `+1.02%` |
| `ALGO-USDT` | `0.1269` | `0.1405` | `0.1238` | `-5.43%` |
| `ATOM-USDT` | `1.7456` | `1.79` | `1.6833` | `+1.60%` |
| `AVAX-USDT` | `11.456` | `12.003` | `10.336` | `+7.87%` |
| `BCH-USDT` | `309.2` | `314.01` | `302.7` | `+0.55%` |
| `BTC-USDT` | `83551.1` | `84544` | `82788.3` | `+0.64%` |
| `CAKE-USDT` | `2.58` | `2.616` | `2.521` | `+0.62%` |
| `DASH-USDT` | `61.43` | `62.65` | `59.04` | `-1.94%` |
| `DGB-USDT` | `0.004482` | `0.004723` | `0.004437` | `-1.01%` |
| `DOGE-USDT` | `0.09425` | `0.09641` | `0.09182` | `+1.35%` |
| `DOT-USDT` | `1.2192` | `1.2357` | `1.1411` | `+5.04%` |
| `ETC-USDT` | `9.1451` | `9.3518` | `8.784` | `+0.86%` |
| `ETH-USDT` | `2676.96` | `2748.49` | `2652.42` | `+0.35%` |
| `LINK-USDT` | `14.5186` | `15.6114` | `14.4131` | `-5.43%` |
| `LTC-USDT` | `67.32` | `69.3` | `66.5` | `-0.79%` |
| `QTUM-USDT` | `0.977` | `1.038` | `0.96` | `-0.40%` |
| `RVN-USDT` | `0.00267` | `0.00283` | `0.0026` | `-3.61%` |
| `SHIB-USDT` | `0.000005807` | `0.000005909` | `0.000005502` | `+3.84%` |
| `SOL-USDT` | `119.63` | `121.67` | `116.36` | `+2.02%` |
| `TRX-USDT` | `0.3346` | `0.3364` | `0.3339` | `-0.02%` |
| `UNI-USDT` | `8.9072` | `9.2869` | `8.4485` | `+2.79%` |
| `XLM-USDT` | `0.2231` | `0.237` | `0.2198` | `-1.50%` |
| `XMR-USDT` | `543.67` | `551.21` | `528.73` | `+1.56%` |
| `XRP-USDT` | `1.49966` | `1.56104` | `1.46611` | `+1.27%` |

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
    "lastUpdated": "2026-09-30 01:25:48 UTC"
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

