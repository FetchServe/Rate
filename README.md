# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-17 08:34:56 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1755` | `0.1793` | `0.1739` | `-1.40%` |
| `ALGO-USDT` | `0.0787` | `0.0801` | `0.0774` | `-0.88%` |
| `ATOM-USDT` | `1.4571` | `1.5041` | `1.4496` | `-2.57%` |
| `AVAX-USDT` | `6.328` | `6.437` | `6.277` | `-0.22%` |
| `BCH-USDT` | `204.72` | `205.86` | `202.1` | `+0.42%` |
| `BTC-USDT` | `63410.7` | `63706.3` | `62715.9` | `+0.55%` |
| `CAKE-USDT` | `1.459` | `1.469` | `1.429` | `+2.09%` |
| `DASH-USDT` | `30.38` | `30.66` | `29.6` | `+2.46%` |
| `DGB-USDT` | `0.004197` | `0.004334` | `0.004021` | `+3.37%` |
| `DOGE-USDT` | `0.07021` | `0.07048` | `0.06901` | `+0.48%` |
| `DOT-USDT` | `0.7581` | `0.7694` | `0.7531` | `-0.21%` |
| `ETC-USDT` | `6.1956` | `6.2371` | `6.0382` | `+0.36%` |
| `ETH-USDT` | `1894.63` | `1912.22` | `1869.4` | `+0.73%` |
| `LINK-USDT` | `9.417` | `9.5648` | `9.2988` | `+0.02%` |
| `LTC-USDT` | `43.92` | `44.82` | `43.85` | `-0.99%` |
| `QTUM-USDT` | `0.683` | `0.687` | `0.671` | `+1.48%` |
| `RVN-USDT` | `0.00286` | `0.00317` | `0.00271` | `+5.53%` |
| `SHIB-USDT` | `0.000004432` | `0.000004505` | `0.000004372` | `-1.57%` |
| `SOL-USDT` | `75.41` | `76` | `74.1` | `-0.07%` |
| `TRX-USDT` | `0.3331` | `0.3331` | `0.3309` | `+0.60%` |
| `UNI-USDT` | `3.2781` | `3.3397` | `3.236` | `+0.00%` |
| `XLM-USDT` | `0.1578` | `0.1597` | `0.156` | `+0.50%` |
| `XMR-USDT` | `417.55` | `420` | `406.86` | `+1.66%` |
| `XRP-USDT` | `1.00027` | `1.00721` | `0.98835` | `-0.16%` |

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
    "lastUpdated": "2026-08-17 08:34:56 UTC"
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

