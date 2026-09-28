# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-28 12:34:23 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2523` | `0.2596` | `0.242` | `-1.94%` |
| `ALGO-USDT` | `0.1316` | `0.1333` | `0.115` | `+11.33%` |
| `ATOM-USDT` | `1.7774` | `1.896` | `1.7474` | `-6.08%` |
| `AVAX-USDT` | `10.569` | `11.086` | `10.336` | `-4.10%` |
| `BCH-USDT` | `313.83` | `339.67` | `304.48` | `-7.36%` |
| `BTC-USDT` | `83359.7` | `85150.4` | `82614.4` | `-1.88%` |
| `CAKE-USDT` | `2.659` | `2.864` | `2.622` | `-5.80%` |
| `DASH-USDT` | `65.84` | `69.7` | `64.19` | `-3.38%` |
| `DGB-USDT` | `0.004554` | `0.004974` | `0.004311` | `+1.22%` |
| `DOGE-USDT` | `0.09432` | `0.09888` | `0.09217` | `-4.11%` |
| `DOT-USDT` | `1.2203` | `1.2814` | `1.1837` | `-2.21%` |
| `ETC-USDT` | `9.3078` | `9.6445` | `8.9632` | `-2.48%` |
| `ETH-USDT` | `2681.78` | `2715.41` | `2636.02` | `-1.20%` |
| `LINK-USDT` | `14.6769` | `15.0111` | `13.5294` | `+2.36%` |
| `LTC-USDT` | `71.84` | `72.49` | `69.45` | `+0.15%` |
| `QTUM-USDT` | `0.98` | `1.031` | `0.953` | `-4.57%` |
| `RVN-USDT` | `0.00264` | `0.00296` | `0.00256` | `-4.00%` |
| `SHIB-USDT` | `0.000005743` | `0.000006006` | `0.000005588` | `-4.09%` |
| `SOL-USDT` | `119.48` | `124.22` | `117.6` | `-3.69%` |
| `TRX-USDT` | `0.336` | `0.336` | `0.333` | `+0.41%` |
| `UNI-USDT` | `9.0635` | `9.913` | `8.7681` | `-8.40%` |
| `XLM-USDT` | `0.2287` | `0.2289` | `0.207` | `+5.00%` |
| `XMR-USDT` | `533.34` | `557.38` | `525.78` | `-4.25%` |
| `XRP-USDT` | `1.51832` | `1.54624` | `1.47` | `-1.43%` |

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
    "lastUpdated": "2026-09-28 12:34:23 UTC"
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

