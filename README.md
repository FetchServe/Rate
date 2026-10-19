# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-19 21:54:36 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2173` | `0.2229` | `0.2153` | `+0.92%` |
| `ALGO-USDT` | `0.1094` | `0.1129` | `0.1077` | `+1.57%` |
| `ATOM-USDT` | `1.7376` | `1.794` | `1.6478` | `+5.43%` |
| `AVAX-USDT` | `9.545` | `9.841` | `9.458` | `+0.86%` |
| `BCH-USDT` | `278.11` | `280.7` | `268.65` | `+3.52%` |
| `BTC-USDT` | `82011.1` | `83144.9` | `81120` | `+1.07%` |
| `CAKE-USDT` | `2.183` | `2.212` | `2.139` | `+2.05%` |
| `DASH-USDT` | `50.39` | `50.42` | `47.3` | `+6.33%` |
| `DGB-USDT` | `0.003351` | `0.003489` | `0.003268` | `-3.76%` |
| `DOGE-USDT` | `0.07941` | `0.08027` | `0.07747` | `+2.50%` |
| `DOT-USDT` | `1.1292` | `1.1812` | `1.0684` | `+5.69%` |
| `ETC-USDT` | `7.7328` | `7.8351` | `7.5583` | `+2.30%` |
| `ETH-USDT` | `2401.3` | `2445.85` | `2366.2` | `+1.46%` |
| `LINK-USDT` | `11.9364` | `12.2687` | `11.7328` | `+1.65%` |
| `LTC-USDT` | `59.23` | `60.44` | `57.48` | `+2.93%` |
| `QTUM-USDT` | `0.851` | `0.861` | `0.827` | `+2.90%` |
| `SHIB-USDT` | `0.000004992` | `0.000005049` | `0.000004867` | `+2.46%` |
| `SOL-USDT` | `104.62` | `106.21` | `101.9` | `+2.59%` |
| `TRX-USDT` | `0.3312` | `0.3335` | `0.3305` | `-0.48%` |
| `UNI-USDT` | `7.2405` | `7.4877` | `6.9335` | `+4.31%` |
| `XLM-USDT` | `0.1769` | `0.1799` | `0.1738` | `+1.78%` |
| `XMR-USDT` | `601.2` | `608` | `580.42` | `+2.66%` |
| `XRP-USDT` | `1.30297` | `1.32157` | `1.27356` | `+2.28%` |

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
    "lastUpdated": "2026-10-19 21:54:36 UTC"
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

