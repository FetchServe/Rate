# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-21 21:58:07 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1451` | `0.1461` | `0.1334` | `+1.61%` |
| `ALGO-USDT` | `0.0745` | `0.0757` | `0.0692` | `+1.91%` |
| `ATOM-USDT` | `1.1731` | `1.2409` | `1.1284` | `-3.95%` |
| `AVAX-USDT` | `6.637` | `6.714` | `6.019` | `+0.98%` |
| `BCH-USDT` | `199.51` | `200.68` | `179.91` | `+3.06%` |
| `BTC-USDT` | `60466.6` | `60987.7` | `55146.1` | `+2.45%` |
| `CAKE-USDT` | `1.479` | `1.494` | `1.377` | `-0.13%` |
| `DASH-USDT` | `34.49` | `34.75` | `30.83` | `+4.57%` |
| `DGB-USDT` | `0.00256` | `0.002626` | `0.002454` | `-1.31%` |
| `DOGE-USDT` | `0.05524` | `0.05569` | `0.05079` | `+2.16%` |
| `DOT-USDT` | `0.6467` | `0.6796` | `0.619` | `-3.67%` |
| `ETC-USDT` | `5.495` | `5.5457` | `5.0959` | `+0.85%` |
| `ETH-USDT` | `1688.72` | `1716.61` | `1538` | `+4.30%` |
| `LINK-USDT` | `8.6251` | `8.7131` | `7.9721` | `+1.30%` |
| `LTC-USDT` | `40.04` | `40.87` | `37.24` | `-0.89%` |
| `QTUM-USDT` | `0.617` | `0.624` | `0.589` | `+3.35%` |
| `SHIB-USDT` | `0.000003618` | `0.000003653` | `0.00000337` | `+1.40%` |
| `SOL-USDT` | `70.44` | `71.11` | `64.9` | `+2.01%` |
| `TRX-USDT` | `0.3056` | `0.3073` | `0.2986` | `+1.15%` |
| `UNI-USDT` | `4.7367` | `4.7883` | `4.1893` | `+6.37%` |
| `XLM-USDT` | `0.1292` | `0.13` | `0.1198` | `+1.01%` |
| `XMR-USDT` | `493.2` | `494.4` | `422.88` | `+8.63%` |
| `XRP-USDT` | `0.93064` | `0.9389` | `0.86` | `+2.37%` |

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
    "lastUpdated": "2026-11-21 21:58:07 UTC"
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

