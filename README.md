# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-19 06:10:20 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2235` | `0.235` | `0.2128` | `+5.02%` |
| `ALGO-USDT` | `0.0968` | `0.0998` | `0.094` | `+2.21%` |
| `ATOM-USDT` | `1.6816` | `1.7824` | `1.6323` | `+2.78%` |
| `AVAX-USDT` | `8.481` | `8.776` | `7.872` | `+7.55%` |
| `BCH-USDT` | `246.65` | `266.09` | `245.08` | `-0.06%` |
| `BTC-USDT` | `81040.3` | `81743.3` | `77414.5` | `+4.54%` |
| `CAKE-USDT` | `2.39` | `2.554` | `2.388` | `-4.74%` |
| `DASH-USDT` | `59.92` | `65.09` | `57.23` | `-1.25%` |
| `DGB-USDT` | `0.00437` | `0.004393` | `0.004022` | `+4.79%` |
| `DOGE-USDT` | `0.08735` | `0.08888` | `0.08409` | `+3.63%` |
| `DOT-USDT` | `1.1262` | `1.1712` | `1.1177` | `-0.01%` |
| `ETC-USDT` | `8.1781` | `8.3663` | `7.769` | `+5.17%` |
| `ETH-USDT` | `2627` | `2646.74` | `2482.11` | `+5.75%` |
| `LINK-USDT` | `12.3428` | `12.4926` | `11.7316` | `+5.03%` |
| `LTC-USDT` | `57.47` | `59.19` | `54.82` | `+4.70%` |
| `QTUM-USDT` | `0.937` | `0.97` | `0.89` | `+5.28%` |
| `RVN-USDT` | `0.00256` | `0.00256` | `0.00243` | `+4.48%` |
| `SHIB-USDT` | `0.000005408` | `0.000005526` | `0.000005308` | `+1.78%` |
| `SOL-USDT` | `111.87` | `114.3` | `105.26` | `+6.06%` |
| `TRX-USDT` | `0.3375` | `0.34` | `0.336` | `+0.44%` |
| `UNI-USDT` | `9.0761` | `9.4425` | `8.4427` | `+6.71%` |
| `XLM-USDT` | `0.1946` | `0.1963` | `0.1848` | `+4.00%` |
| `XMR-USDT` | `573.77` | `606.42` | `524.27` | `+8.55%` |
| `XRP-USDT` | `1.42241` | `1.43861` | `1.31594` | `+7.78%` |

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
    "lastUpdated": "2026-09-19 06:10:20 UTC"
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

