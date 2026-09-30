# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-30 14:00:26 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2515` | `0.2569` | `0.2399` | `-0.15%` |
| `ALGO-USDT` | `0.1251` | `0.1326` | `0.1224` | `-4.35%` |
| `ATOM-USDT` | `1.7406` | `1.7841` | `1.6998` | `-1.12%` |
| `AVAX-USDT` | `11.1` | `11.72` | `10.981` | `-4.52%` |
| `BCH-USDT` | `309.95` | `318.35` | `303.05` | `-0.62%` |
| `BTC-USDT` | `84605.5` | `85607.9` | `82913.7` | `+0.47%` |
| `CAKE-USDT` | `2.635` | `2.695` | `2.521` | `+1.69%` |
| `DASH-USDT` | `62` | `63.46` | `59.76` | `+0.04%` |
| `DGB-USDT` | `0.00445` | `0.004684` | `0.004363` | `-4.36%` |
| `DOGE-USDT` | `0.09619` | `0.0981` | `0.09278` | `+0.34%` |
| `DOT-USDT` | `1.2412` | `1.2619` | `1.1591` | `+2.60%` |
| `ETC-USDT` | `9.1374` | `9.3468` | `8.9732` | `-1.44%` |
| `ETH-USDT` | `2708.56` | `2737.97` | `2658.12` | `-0.67%` |
| `LINK-USDT` | `14.563` | `15.1776` | `14.1891` | `-3.76%` |
| `LTC-USDT` | `67.37` | `68.71` | `66.34` | `-1.39%` |
| `QTUM-USDT` | `1.01` | `1.027` | `0.968` | `+1.50%` |
| `RVN-USDT` | `0.00261` | `0.00283` | `0.0026` | `-4.74%` |
| `SHIB-USDT` | `0.000005897` | `0.000005993` | `0.00000568` | `+0.54%` |
| `SOL-USDT` | `120.92` | `122.8` | `117.39` | `-0.07%` |
| `TRX-USDT` | `0.3396` | `0.342` | `0.3339` | `+1.37%` |
| `UNI-USDT` | `8.9765` | `9.2008` | `8.7259` | `-0.94%` |
| `XLM-USDT` | `0.2268` | `0.233` | `0.2192` | `-2.40%` |
| `XMR-USDT` | `545.54` | `551.21` | `536.71` | `+0.65%` |
| `XRP-USDT` | `1.51893` | `1.56104` | `1.47497` | `-1.87%` |

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
    "lastUpdated": "2026-09-30 14:00:26 UTC"
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

