# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-01 06:25:45 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.201` | `0.203` | `0.1937` | `+2.76%` |
| `ALGO-USDT` | `0.09` | `0.0911` | `0.0842` | `+5.88%` |
| `ATOM-USDT` | `1.4983` | `1.5` | `1.4569` | `+1.09%` |
| `AVAX-USDT` | `7.281` | `7.335` | `7.134` | `+1.01%` |
| `BCH-USDT` | `249.52` | `251.75` | `243.9` | `+1.33%` |
| `BTC-USDT` | `78822.2` | `79246.9` | `77703.4` | `+1.07%` |
| `CAKE-USDT` | `1.863` | `1.895` | `1.827` | `+1.63%` |
| `DASH-USDT` | `46.54` | `48.5` | `41.45` | `+11.55%` |
| `DGB-USDT` | `0.004754` | `0.00484` | `0.004597` | `-1.14%` |
| `DOGE-USDT` | `0.08344` | `0.08395` | `0.08203` | `+0.89%` |
| `DOT-USDT` | `0.8604` | `0.8615` | `0.82` | `+3.86%` |
| `ETC-USDT` | `7.3534` | `7.6` | `7.1983` | `+1.88%` |
| `ETH-USDT` | `2473.65` | `2490` | `2433.51` | `+1.45%` |
| `LINK-USDT` | `11.4456` | `11.5204` | `11.1597` | `+1.63%` |
| `LTC-USDT` | `49.05` | `49.15` | `48.11` | `+0.80%` |
| `QTUM-USDT` | `0.831` | `0.837` | `0.807` | `+1.71%` |
| `RVN-USDT` | `0.00299` | `0.00311` | `0.00293` | `-0.99%` |
| `SHIB-USDT` | `0.000005165` | `0.000005223` | `0.000004995` | `+2.58%` |
| `SOL-USDT` | `103.76` | `104.98` | `102.19` | `+1.25%` |
| `TRX-USDT` | `0.3316` | `0.3377` | `0.3315` | `-1.51%` |
| `UNI-USDT` | `5.6391` | `5.647` | `5.0478` | `+9.88%` |
| `XLM-USDT` | `0.1781` | `0.1799` | `0.1746` | `+1.07%` |
| `XMR-USDT` | `519.19` | `550` | `501` | `+1.25%` |
| `XRP-USDT` | `1.38547` | `1.39645` | `1.35744` | `+1.62%` |

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
    "lastUpdated": "2026-09-01 06:25:45 UTC"
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

