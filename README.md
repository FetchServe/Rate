# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-10-01 02:15:55 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2474` | `0.2569` | `0.2415` | `+0.61%` |
| `ALGO-USDT` | `0.1244` | `0.1282` | `0.1224` | `-0.63%` |
| `ATOM-USDT` | `1.7451` | `1.767` | `1.6998` | `+0.93%` |
| `AVAX-USDT` | `10.892` | `11.414` | `10.806` | `-4.31%` |
| `BCH-USDT` | `307.06` | `318.35` | `303.58` | `-0.25%` |
| `BTC-USDT` | `83594.5` | `85607.9` | `82965` | `+0.11%` |
| `CAKE-USDT` | `2.576` | `2.695` | `2.54` | `+0.19%` |
| `DASH-USDT` | `60` | `63.46` | `59.46` | `-2.04%` |
| `DGB-USDT` | `0.00448` | `0.00467` | `0.004311` | `+0.90%` |
| `DOGE-USDT` | `0.09489` | `0.0981` | `0.09283` | `+0.89%` |
| `DOT-USDT` | `1.2268` | `1.2791` | `1.1889` | `+1.65%` |
| `ETC-USDT` | `8.9241` | `9.2951` | `8.7795` | `-1.65%` |
| `ETH-USDT` | `2690.49` | `2737.97` | `2658.12` | `+0.68%` |
| `LINK-USDT` | `14.3181` | `14.8125` | `14.0555` | `-0.74%` |
| `LTC-USDT` | `67.07` | `68.25` | `65.65` | `-0.02%` |
| `QTUM-USDT` | `0.995` | `1.027` | `0.977` | `+1.84%` |
| `RVN-USDT` | `0.00258` | `0.00271` | `0.00257` | `-3.37%` |
| `SHIB-USDT` | `0.000005742` | `0.000005993` | `0.000005695` | `-0.98%` |
| `SOL-USDT` | `118.22` | `122.8` | `117.06` | `-1.21%` |
| `TRX-USDT` | `0.338` | `0.342` | `0.3349` | `+0.89%` |
| `UNI-USDT` | `8.8311` | `9.2008` | `8.7259` | `-0.05%` |
| `XLM-USDT` | `0.2281` | `0.2318` | `0.2192` | `+2.84%` |
| `XMR-USDT` | `546.21` | `549.14` | `536.38` | `+0.59%` |
| `XRP-USDT` | `1.49007` | `1.54399` | `1.48534` | `-0.57%` |

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
    "lastUpdated": "2026-10-01 02:15:55 UTC"
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

