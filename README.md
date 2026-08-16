# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-16 11:13:31 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1769` | `0.1793` | `0.1756` | `-1.06%` |
| `ALGO-USDT` | `0.0792` | `0.0803` | `0.0787` | `-0.62%` |
| `ATOM-USDT` | `1.493` | `1.5041` | `1.4638` | `+0.71%` |
| `AVAX-USDT` | `6.377` | `6.598` | `6.223` | `-3.11%` |
| `BCH-USDT` | `204.1` | `206.97` | `202.86` | `-0.26%` |
| `BTC-USDT` | `62996.3` | `63163.5` | `62943.8` | `-0.04%` |
| `CAKE-USDT` | `1.46` | `1.46` | `1.424` | `+1.60%` |
| `DASH-USDT` | `29.77` | `30.23` | `29.49` | `-1.03%` |
| `DGB-USDT` | `0.00406` | `0.0041` | `0.0039` | `+2.49%` |
| `DOGE-USDT` | `0.06978` | `0.07013` | `0.06952` | `-0.37%` |
| `DOT-USDT` | `0.7598` | `0.7805` | `0.756` | `-2.48%` |
| `ETC-USDT` | `6.1771` | `6.2795` | `6.159` | `-1.48%` |
| `ETH-USDT` | `1880.78` | `1886.39` | `1877.12` | `+0.00%` |
| `LINK-USDT` | `9.4235` | `9.6315` | `9.2778` | `+0.66%` |
| `LTC-USDT` | `44.37` | `44.44` | `43.97` | `+0.63%` |
| `QTUM-USDT` | `0.673` | `0.679` | `0.67` | `+0.00%` |
| `RVN-USDT` | `0.00275` | `0.00286` | `0.00262` | `+4.96%` |
| `SHIB-USDT` | `0.000004472` | `0.000004598` | `0.000004462` | `-2.27%` |
| `SOL-USDT` | `75.24` | `75.72` | `75.17` | `-0.05%` |
| `TRX-USDT` | `0.3315` | `0.3326` | `0.3308` | `+0.06%` |
| `UNI-USDT` | `3.2661` | `3.3025` | `3.2174` | `+0.16%` |
| `XLM-USDT` | `0.1571` | `0.1598` | `0.1566` | `-0.75%` |
| `XMR-USDT` | `410.4` | `414.24` | `400.27` | `+1.13%` |
| `XRP-USDT` | `1.0004` | `1.0065` | `0.99733` | `-0.32%` |

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
    "lastUpdated": "2026-08-16 11:13:31 UTC"
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

