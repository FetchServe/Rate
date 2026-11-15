# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-15 20:04:00 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1544` | `0.1567` | `0.1426` | `-0.12%` |
| `ALGO-USDT` | `0.0797` | `0.0807` | `0.0748` | `+1.14%` |
| `ATOM-USDT` | `1.3018` | `1.328` | `1.2192` | `-0.18%` |
| `AVAX-USDT` | `7.23` | `7.443` | `6.744` | `-2.80%` |
| `BCH-USDT` | `208.73` | `212.38` | `195.75` | `+0.09%` |
| `BTC-USDT` | `64825.4` | `66124.7` | `61987.9` | `-1.59%` |
| `CAKE-USDT` | `1.583` | `1.632` | `1.517` | `-0.75%` |
| `DASH-USDT` | `38.03` | `39.37` | `34.44` | `+3.31%` |
| `DGB-USDT` | `0.00272` | `0.002775` | `0.00258` | `-0.36%` |
| `DOGE-USDT` | `0.05893` | `0.05988` | `0.05544` | `-1.58%` |
| `DOT-USDT` | `0.7344` | `0.7484` | `0.682` | `-1.87%` |
| `ETC-USDT` | `5.9951` | `6.0404` | `5.621` | `-0.61%` |
| `ETH-USDT` | `1820.6` | `1845.76` | `1711` | `-1.03%` |
| `LINK-USDT` | `9.2241` | `9.3778` | `8.58` | `+1.31%` |
| `LTC-USDT` | `45.28` | `45.8` | `42.68` | `-0.83%` |
| `QTUM-USDT` | `0.654` | `0.667` | `0.64` | `+1.71%` |
| `SHIB-USDT` | `0.000003927` | `0.000003972` | `0.000003697` | `-0.32%` |
| `SOL-USDT` | `71.52` | `73.27` | `67.42` | `-1.24%` |
| `TRX-USDT` | `0.3053` | `0.3097` | `0.3037` | `-1.13%` |
| `UNI-USDT` | `5.1825` | `5.2211` | `4.6208` | `+5.10%` |
| `XLM-USDT` | `0.1395` | `0.141` | `0.1301` | `+1.75%` |
| `XMR-USDT` | `501.97` | `509.77` | `455.75` | `+0.23%` |
| `XRP-USDT` | `0.95862` | `0.97944` | `0.89308` | `+0.34%` |

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
    "lastUpdated": "2026-11-15 20:04:00 UTC"
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

