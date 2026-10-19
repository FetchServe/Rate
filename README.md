# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-19 11:01:46 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2185` | `0.2229` | `0.2111` | `-0.90%` |
| `ALGO-USDT` | `0.1101` | `0.1129` | `0.1059` | `-0.36%` |
| `ATOM-USDT` | `1.7385` | `1.7497` | `1.6237` | `+1.77%` |
| `AVAX-USDT` | `9.659` | `9.841` | `9.261` | `-1.47%` |
| `BCH-USDT` | `277.35` | `280.25` | `264.41` | `+0.69%` |
| `BTC-USDT` | `82364.6` | `83144.9` | `80690.5` | `+0.33%` |
| `CAKE-USDT` | `2.167` | `2.212` | `2.106` | `-1.18%` |
| `DASH-USDT` | `48.63` | `49.59` | `46.25` | `-1.39%` |
| `DGB-USDT` | `0.003373` | `0.00378` | `0.003268` | `-2.31%` |
| `DOGE-USDT` | `0.0791` | `0.08027` | `0.07609` | `-0.30%` |
| `DOT-USDT` | `1.103` | `1.1381` | `1.0469` | `-0.53%` |
| `ETC-USDT` | `7.7497` | `7.8351` | `7.4339` | `-0.05%` |
| `ETH-USDT` | `2422.22` | `2445.85` | `2329.43` | `+0.19%` |
| `LINK-USDT` | `12.059` | `12.2687` | `11.5368` | `+0.46%` |
| `LTC-USDT` | `59.7` | `60.24` | `56.7` | `+0.74%` |
| `QTUM-USDT` | `0.855` | `0.861` | `0.825` | `-0.69%` |
| `SHIB-USDT` | `0.000005007` | `0.000005047` | `0.000004801` | `+0.52%` |
| `SOL-USDT` | `104.77` | `106.21` | `100.44` | `+0.78%` |
| `TRX-USDT` | `0.3312` | `0.3335` | `0.3305` | `-0.60%` |
| `UNI-USDT` | `7.3397` | `7.4877` | `6.813` | `+1.03%` |
| `XLM-USDT` | `0.1766` | `0.1799` | `0.1718` | `-0.56%` |
| `XMR-USDT` | `588.98` | `607.76` | `572.73` | `+0.78%` |
| `XRP-USDT` | `1.3023` | `1.32157` | `1.25603` | `+0.40%` |

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
    "lastUpdated": "2026-10-19 11:01:46 UTC"
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

