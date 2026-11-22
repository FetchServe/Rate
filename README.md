# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-22 01:55:48 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1445` | `0.1461` | `0.1334` | `+0.83%` |
| `ALGO-USDT` | `0.0744` | `0.0757` | `0.0692` | `+1.36%` |
| `ATOM-USDT` | `1.1698` | `1.223` | `1.1284` | `-3.86%` |
| `AVAX-USDT` | `6.588` | `6.714` | `6.019` | `+1.35%` |
| `BCH-USDT` | `200.07` | `200.68` | `179.91` | `+2.86%` |
| `BTC-USDT` | `60147.3` | `60987.7` | `55146.1` | `+1.95%` |
| `CAKE-USDT` | `1.483` | `1.487` | `1.377` | `+0.00%` |
| `DASH-USDT` | `34.88` | `35` | `30.83` | `+6.24%` |
| `DGB-USDT` | `0.00258` | `0.002626` | `0.002454` | `+0.66%` |
| `DOGE-USDT` | `0.05527` | `0.05569` | `0.05079` | `+1.43%` |
| `DOT-USDT` | `0.6546` | `0.6691` | `0.619` | `-1.80%` |
| `ETC-USDT` | `5.4925` | `5.5457` | `5.0959` | `+0.09%` |
| `ETH-USDT` | `1687.97` | `1716.61` | `1538` | `+3.91%` |
| `LINK-USDT` | `8.6004` | `8.7131` | `7.9721` | `+0.33%` |
| `LTC-USDT` | `39.89` | `40.75` | `37.24` | `-1.84%` |
| `QTUM-USDT` | `0.615` | `0.624` | `0.589` | `+0.81%` |
| `SHIB-USDT` | `0.000003652` | `0.000003653` | `0.00000337` | `+1.92%` |
| `SOL-USDT` | `70.39` | `71.11` | `64.9` | `+2.32%` |
| `TRX-USDT` | `0.3057` | `0.3073` | `0.2986` | `+1.19%` |
| `UNI-USDT` | `4.741` | `4.7883` | `4.1893` | `+5.55%` |
| `XLM-USDT` | `0.1286` | `0.13` | `0.1198` | `+0.94%` |
| `XMR-USDT` | `491.94` | `495.32` | `422.88` | `+8.35%` |
| `XRP-USDT` | `0.93243` | `0.9389` | `0.86` | `+2.45%` |

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
    "lastUpdated": "2026-11-22 01:55:48 UTC"
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

