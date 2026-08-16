# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-16 10:46:55 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1763` | `0.1793` | `0.1756` | `-1.50%` |
| `ALGO-USDT` | `0.079` | `0.0803` | `0.0787` | `-0.50%` |
| `ATOM-USDT` | `1.4938` | `1.5041` | `1.4638` | `+0.68%` |
| `AVAX-USDT` | `6.371` | `6.598` | `6.223` | `-3.41%` |
| `BCH-USDT` | `203.67` | `206.97` | `202.86` | `-0.52%` |
| `BTC-USDT` | `62997.7` | `63163.5` | `62943.8` | `-0.06%` |
| `CAKE-USDT` | `1.455` | `1.457` | `1.424` | `+1.60%` |
| `DASH-USDT` | `29.76` | `30.23` | `29.49` | `-0.86%` |
| `DGB-USDT` | `0.004032` | `0.0041` | `0.0039` | `+1.56%` |
| `DOGE-USDT` | `0.06976` | `0.07013` | `0.06952` | `-0.35%` |
| `DOT-USDT` | `0.7591` | `0.7842` | `0.756` | `-2.71%` |
| `ETC-USDT` | `6.1725` | `6.2801` | `6.159` | `-1.71%` |
| `ETH-USDT` | `1880.7` | `1886.39` | `1877.12` | `+0.03%` |
| `LINK-USDT` | `9.3982` | `9.6315` | `9.2778` | `+0.52%` |
| `LTC-USDT` | `44.36` | `44.44` | `43.97` | `+0.65%` |
| `QTUM-USDT` | `0.673` | `0.679` | `0.67` | `+0.00%` |
| `RVN-USDT` | `0.00274` | `0.00286` | `0.00262` | `+4.18%` |
| `SHIB-USDT` | `0.000004468` | `0.000004598` | `0.000004462` | `-2.40%` |
| `SOL-USDT` | `75.24` | `75.72` | `75.17` | `-0.07%` |
| `TRX-USDT` | `0.3315` | `0.3326` | `0.3308` | `-0.24%` |
| `UNI-USDT` | `3.2672` | `3.3025` | `3.2174` | `+0.05%` |
| `XLM-USDT` | `0.1568` | `0.1598` | `0.1566` | `-0.94%` |
| `XMR-USDT` | `408.33` | `414.24` | `400.27` | `+0.59%` |
| `XRP-USDT` | `0.99978` | `1.0065` | `0.99733` | `-0.29%` |

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
    "lastUpdated": "2026-08-16 10:46:55 UTC"
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

