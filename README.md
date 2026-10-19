# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-19 17:37:31 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2173` | `0.2229` | `0.2111` | `+0.64%` |
| `ALGO-USDT` | `0.1085` | `0.1129` | `0.1059` | `+0.46%` |
| `ATOM-USDT` | `1.738` | `1.794` | `1.6237` | `+4.04%` |
| `AVAX-USDT` | `9.58` | `9.841` | `9.261` | `+0.50%` |
| `BCH-USDT` | `276.42` | `280.7` | `264.41` | `+2.50%` |
| `BTC-USDT` | `81928.2` | `83144.9` | `80690.5` | `+0.92%` |
| `CAKE-USDT` | `2.169` | `2.212` | `2.106` | `+0.88%` |
| `DASH-USDT` | `49.41` | `49.75` | `46.25` | `+3.43%` |
| `DGB-USDT` | `0.00337` | `0.00349` | `0.003268` | `-2.65%` |
| `DOGE-USDT` | `0.07907` | `0.08027` | `0.07609` | `+1.38%` |
| `DOT-USDT` | `1.1526` | `1.1812` | `1.0469` | `+6.84%` |
| `ETC-USDT` | `7.7124` | `7.8351` | `7.4339` | `+1.31%` |
| `ETH-USDT` | `2398.97` | `2445.85` | `2329.43` | `+1.11%` |
| `LINK-USDT` | `11.9264` | `12.2687` | `11.5368` | `+1.27%` |
| `LTC-USDT` | `59.89` | `60.44` | `56.7` | `+2.95%` |
| `QTUM-USDT` | `0.85` | `0.861` | `0.825` | `+0.47%` |
| `SHIB-USDT` | `0.000004995` | `0.000005049` | `0.000004801` | `+1.71%` |
| `SOL-USDT` | `104.13` | `106.21` | `100.44` | `+1.95%` |
| `TRX-USDT` | `0.3311` | `0.3335` | `0.3305` | `-0.45%` |
| `UNI-USDT` | `7.2863` | `7.4877` | `6.813` | `+3.94%` |
| `XLM-USDT` | `0.1761` | `0.1799` | `0.1718` | `+1.09%` |
| `XMR-USDT` | `591.06` | `608` | `572.73` | `+0.35%` |
| `XRP-USDT` | `1.30132` | `1.32157` | `1.25603` | `+2.19%` |

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
    "lastUpdated": "2026-10-19 17:37:31 UTC"
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

