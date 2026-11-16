# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-16 00:06:22 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1553` | `0.1567` | `0.1426` | `+5.35%` |
| `ALGO-USDT` | `0.08` | `0.0807` | `0.0756` | `+3.09%` |
| `ATOM-USDT` | `1.3099` | `1.328` | `1.2268` | `+3.96%` |
| `AVAX-USDT` | `7.301` | `7.34` | `6.744` | `+3.15%` |
| `BCH-USDT` | `210.88` | `212.38` | `195.75` | `+5.24%` |
| `BTC-USDT` | `65247.7` | `66124.7` | `61987.9` | `+1.81%` |
| `CAKE-USDT` | `1.599` | `1.632` | `1.536` | `+1.45%` |
| `DASH-USDT` | `37.83` | `39.37` | `34.6` | `+6.23%` |
| `DGB-USDT` | `0.002765` | `0.002796` | `0.00258` | `+1.13%` |
| `DOGE-USDT` | `0.05977` | `0.06012` | `0.05546` | `+4.29%` |
| `DOT-USDT` | `0.7356` | `0.7419` | `0.682` | `+4.13%` |
| `ETC-USDT` | `6.0361` | `6.0451` | `5.6508` | `+4.34%` |
| `ETH-USDT` | `1833.2` | `1845.76` | `1711` | `+3.69%` |
| `LINK-USDT` | `9.2864` | `9.3778` | `8.6254` | `+4.70%` |
| `LTC-USDT` | `45.5` | `45.8` | `42.68` | `+2.36%` |
| `QTUM-USDT` | `0.652` | `0.667` | `0.64` | `+0.46%` |
| `SHIB-USDT` | `0.000003949` | `0.000003972` | `0.000003705` | `+3.21%` |
| `SOL-USDT` | `72.58` | `73.27` | `67.42` | `+3.27%` |
| `TRX-USDT` | `0.3052` | `0.3097` | `0.3037` | `-0.58%` |
| `UNI-USDT` | `5.1683` | `5.2267` | `4.6818` | `+6.34%` |
| `XLM-USDT` | `0.1413` | `0.142` | `0.1301` | `+4.35%` |
| `XMR-USDT` | `500.82` | `509.77` | `463.95` | `+6.52%` |
| `XRP-USDT` | `0.97113` | `0.97944` | `0.89936` | `+5.71%` |

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
    "lastUpdated": "2026-11-16 00:06:22 UTC"
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

