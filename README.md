# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-27 18:50:25 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2054` | `0.2072` | `0.2013` | `+0.04%` |
| `ALGO-USDT` | `0.1042` | `0.1062` | `0.1018` | `+0.00%` |
| `ATOM-USDT` | `1.6154` | `1.6491` | `1.6048` | `-0.99%` |
| `AVAX-USDT` | `8.881` | `8.987` | `8.667` | `-0.41%` |
| `BCH-USDT` | `289.84` | `295.1` | `277.23` | `+4.18%` |
| `BTC-USDT` | `80636` | `80816.3` | `79509.3` | `+0.62%` |
| `CAKE-USDT` | `2.083` | `2.164` | `2.042` | `-1.97%` |
| `DASH-USDT` | `54.77` | `55.86` | `52.32` | `+3.67%` |
| `DGB-USDT` | `0.003312` | `0.00345` | `0.003216` | `-2.04%` |
| `DOGE-USDT` | `0.07835` | `0.07871` | `0.07668` | `+1.47%` |
| `DOT-USDT` | `1.0045` | `1.0146` | `0.9775` | `-0.18%` |
| `ETC-USDT` | `7.6038` | `7.6451` | `7.471` | `+0.77%` |
| `ETH-USDT` | `2345.64` | `2357.5` | `2297.79` | `+1.17%` |
| `LINK-USDT` | `11.4837` | `11.5119` | `11.2288` | `+0.80%` |
| `LTC-USDT` | `56.7` | `56.99` | `55.74` | `+0.53%` |
| `QTUM-USDT` | `0.824` | `0.825` | `0.808` | `-0.12%` |
| `SHIB-USDT` | `0.000004883` | `0.000004903` | `0.000004798` | `+0.53%` |
| `SOL-USDT` | `101` | `101.31` | `99.17` | `+0.45%` |
| `TRX-USDT` | `0.3296` | `0.3306` | `0.3273` | `-0.27%` |
| `UNI-USDT` | `7.0939` | `7.2101` | `6.9453` | `+0.71%` |
| `XLM-USDT` | `0.1702` | `0.1705` | `0.1665` | `+1.24%` |
| `XMR-USDT` | `599.99` | `613.23` | `585.65` | `+0.81%` |
| `XRP-USDT` | `1.32425` | `1.32877` | `1.28532` | `+2.22%` |

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
    "lastUpdated": "2026-10-27 18:50:25 UTC"
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

