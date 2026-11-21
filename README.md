# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-21 16:52:30 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1447` | `0.1455` | `0.1334` | `+2.98%` |
| `ALGO-USDT` | `0.0753` | `0.0757` | `0.0692` | `+3.00%` |
| `ATOM-USDT` | `1.1907` | `1.2409` | `1.1284` | `-1.67%` |
| `AVAX-USDT` | `6.624` | `6.714` | `6.019` | `+1.34%` |
| `BCH-USDT` | `198.5` | `200.68` | `179.91` | `+4.12%` |
| `BTC-USDT` | `60079.3` | `60987.7` | `55146.1` | `+0.83%` |
| `CAKE-USDT` | `1.485` | `1.494` | `1.377` | `+0.00%` |
| `DASH-USDT` | `34.3` | `34.34` | `30.83` | `+3.37%` |
| `DGB-USDT` | `0.002569` | `0.002652` | `0.002454` | `-0.42%` |
| `DOGE-USDT` | `0.05511` | `0.05569` | `0.05079` | `+1.90%` |
| `DOT-USDT` | `0.6572` | `0.6796` | `0.619` | `-0.66%` |
| `ETC-USDT` | `5.487` | `5.5457` | `5.0959` | `+1.57%` |
| `ETH-USDT` | `1684.23` | `1716.61` | `1538` | `+2.26%` |
| `LINK-USDT` | `8.6136` | `8.7131` | `7.9721` | `+2.59%` |
| `LTC-USDT` | `39.85` | `40.87` | `37.24` | `-0.49%` |
| `QTUM-USDT` | `0.622` | `0.624` | `0.589` | `+2.47%` |
| `SHIB-USDT` | `0.00000363` | `0.000003653` | `0.00000337` | `+2.48%` |
| `SOL-USDT` | `70.75` | `71.11` | `64.9` | `+1.78%` |
| `TRX-USDT` | `0.3057` | `0.3073` | `0.2986` | `+1.05%` |
| `UNI-USDT` | `4.7347` | `4.7883` | `4.1893` | `+6.06%` |
| `XLM-USDT` | `0.1286` | `0.1299` | `0.1198` | `+0.54%` |
| `XMR-USDT` | `481.8` | `483.74` | `422.88` | `+8.55%` |
| `XRP-USDT` | `0.92931` | `0.93455` | `0.86` | `+1.72%` |

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
    "lastUpdated": "2026-11-21 16:52:30 UTC"
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

