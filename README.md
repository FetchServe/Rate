# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-17 16:19:00 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1752` | `0.1793` | `0.1725` | `-1.07%` |
| `ALGO-USDT` | `0.0787` | `0.0801` | `0.0774` | `-0.12%` |
| `ATOM-USDT` | `1.4162` | `1.4858` | `1.4096` | `-4.64%` |
| `AVAX-USDT` | `6.314` | `6.435` | `6.277` | `-1.81%` |
| `BCH-USDT` | `205.47` | `205.86` | `202.1` | `+0.31%` |
| `BTC-USDT` | `64080.8` | `64221.5` | `62715.9` | `+1.22%` |
| `CAKE-USDT` | `1.465` | `1.472` | `1.444` | `+0.34%` |
| `DASH-USDT` | `30.42` | `30.66` | `29.8` | `+0.42%` |
| `DGB-USDT` | `0.003969` | `0.004334` | `0.003969` | `-4.68%` |
| `DOGE-USDT` | `0.07035` | `0.07057` | `0.06901` | `+0.29%` |
| `DOT-USDT` | `0.7564` | `0.7694` | `0.7531` | `-1.40%` |
| `ETC-USDT` | `6.1787` | `6.2371` | `6.0382` | `-0.44%` |
| `ETH-USDT` | `1908.99` | `1915.42` | `1869.4` | `+1.14%` |
| `LINK-USDT` | `9.5339` | `9.5761` | `9.3503` | `+1.27%` |
| `LTC-USDT` | `44.41` | `44.68` | `43.83` | `-0.55%` |
| `QTUM-USDT` | `0.682` | `0.687` | `0.671` | `+0.14%` |
| `RVN-USDT` | `0.00287` | `0.00317` | `0.00279` | `+2.50%` |
| `SHIB-USDT` | `0.00000446` | `0.000004518` | `0.000004372` | `-0.93%` |
| `SOL-USDT` | `76.03` | `76.22` | `74.1` | `+0.55%` |
| `TRX-USDT` | `0.3294` | `0.3349` | `0.3285` | `-0.90%` |
| `UNI-USDT` | `3.2914` | `3.3397` | `3.236` | `-1.40%` |
| `XLM-USDT` | `0.1582` | `0.1614` | `0.156` | `-0.31%` |
| `XMR-USDT` | `412.7` | `421.45` | `406.86` | `-0.20%` |
| `XRP-USDT` | `1.00342` | `1.00854` | `0.98835` | `+0.00%` |

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
    "lastUpdated": "2026-08-17 16:19:00 UTC"
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

