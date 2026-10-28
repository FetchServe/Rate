# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-28 20:00:26 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2075` | `0.2087` | `0.2008` | `+1.02%` |
| `ALGO-USDT` | `0.1052` | `0.1053` | `0.1007` | `+0.95%` |
| `ATOM-USDT` | `1.6471` | `1.658` | `1.602` | `+2.01%` |
| `AVAX-USDT` | `9.054` | `9.084` | `8.793` | `+1.85%` |
| `BCH-USDT` | `289.36` | `304.81` | `282.5` | `+0.02%` |
| `BTC-USDT` | `81642` | `81800` | `80409.4` | `+1.02%` |
| `CAKE-USDT` | `2.122` | `2.122` | `2.067` | `+1.87%` |
| `DASH-USDT` | `53.84` | `55.8` | `52.67` | `-3.00%` |
| `DGB-USDT` | `0.003371` | `0.003448` | `0.003321` | `+1.50%` |
| `DOGE-USDT` | `0.08032` | `0.08066` | `0.07826` | `+2.40%` |
| `DOT-USDT` | `1.0328` | `1.0332` | `0.9877` | `+3.52%` |
| `ETC-USDT` | `7.6727` | `7.731` | `7.4968` | `+0.95%` |
| `ETH-USDT` | `2375.94` | `2387.81` | `2323.41` | `+1.19%` |
| `LINK-USDT` | `11.8777` | `11.8904` | `11.442` | `+3.35%` |
| `LTC-USDT` | `59.54` | `59.56` | `56.59` | `+4.89%` |
| `QTUM-USDT` | `0.84` | `0.843` | `0.824` | `+1.94%` |
| `SHIB-USDT` | `0.00000501` | `0.000005011` | `0.000004847` | `+2.57%` |
| `SOL-USDT` | `103.2` | `103.67` | `100.45` | `+2.00%` |
| `TRX-USDT` | `0.3297` | `0.3327` | `0.3295` | `-0.12%` |
| `UNI-USDT` | `7.2481` | `7.271` | `6.9746` | `+2.35%` |
| `XLM-USDT` | `0.1737` | `0.1737` | `0.1687` | `+2.11%` |
| `XMR-USDT` | `602.99` | `620` | `592.35` | `+0.27%` |
| `XRP-USDT` | `1.33689` | `1.34406` | `1.30817` | `+0.96%` |

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
    "lastUpdated": "2026-10-28 20:00:26 UTC"
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

