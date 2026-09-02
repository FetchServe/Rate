# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-02 19:35:00 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1967` | `0.1993` | `0.192` | `-0.10%` |
| `ALGO-USDT` | `0.0918` | `0.093` | `0.0869` | `+3.61%` |
| `ATOM-USDT` | `1.459` | `1.4816` | `1.4394` | `-1.52%` |
| `AVAX-USDT` | `7.147` | `7.257` | `7.044` | `-1.21%` |
| `BCH-USDT` | `243.6` | `250.02` | `241.28` | `-1.33%` |
| `BTC-USDT` | `77134.1` | `77757.6` | `76271.4` | `-0.25%` |
| `CAKE-USDT` | `1.799` | `1.85` | `1.783` | `-0.27%` |
| `DASH-USDT` | `42.18` | `44.06` | `41.14` | `-3.52%` |
| `DGB-USDT` | `0.004289` | `0.004396` | `0.004204` | `-1.15%` |
| `DOGE-USDT` | `0.08113` | `0.08213` | `0.08014` | `-1.08%` |
| `DOT-USDT` | `0.8594` | `0.8934` | `0.838` | `-1.86%` |
| `ETC-USDT` | `7.2145` | `7.326` | `7.1291` | `-1.45%` |
| `ETH-USDT` | `2384.1` | `2428.7` | `2356.5` | `-1.47%` |
| `LINK-USDT` | `11.0794` | `11.3027` | `10.9131` | `-1.25%` |
| `LTC-USDT` | `49.62` | `50.09` | `48.5` | `+0.16%` |
| `QTUM-USDT` | `0.815` | `0.827` | `0.809` | `-0.97%` |
| `RVN-USDT` | `0.00291` | `0.00299` | `0.00289` | `-2.02%` |
| `SHIB-USDT` | `0.000005154` | `0.000005243` | `0.000005055` | `-0.40%` |
| `SOL-USDT` | `99.16` | `100.69` | `97.4` | `-0.79%` |
| `TRX-USDT` | `0.3246` | `0.3285` | `0.3216` | `+0.40%` |
| `UNI-USDT` | `5.7992` | `6.3772` | `5.6333` | `+2.70%` |
| `XLM-USDT` | `0.1734` | `0.1767` | `0.1713` | `-1.70%` |
| `XMR-USDT` | `534.72` | `535.61` | `493` | `+7.53%` |
| `XRP-USDT` | `1.34352` | `1.36352` | `1.31004` | `-1.39%` |

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
    "lastUpdated": "2026-09-02 19:35:00 UTC"
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

