# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-25 17:44:13 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2063` | `0.2094` | `0.2023` | `+1.12%` |
| `ALGO-USDT` | `0.1066` | `0.1067` | `0.1015` | `+3.49%` |
| `ATOM-USDT` | `1.658` | `1.6584` | `1.6028` | `+1.38%` |
| `AVAX-USDT` | `8.953` | `9.027` | `8.744` | `+1.32%` |
| `BCH-USDT` | `280.22` | `280.22` | `270.46` | `+3.02%` |
| `BTC-USDT` | `80794.9` | `81021` | `80100.3` | `+0.79%` |
| `CAKE-USDT` | `2.071` | `2.096` | `2.04` | `+1.51%` |
| `DASH-USDT` | `52.27` | `54.16` | `49.56` | `+5.46%` |
| `DGB-USDT` | `0.003406` | `0.003501` | `0.003262` | `+2.62%` |
| `DOGE-USDT` | `0.07748` | `0.07807` | `0.07595` | `+1.48%` |
| `DOT-USDT` | `1.0451` | `1.0565` | `1.0121` | `+1.33%` |
| `ETC-USDT` | `7.5714` | `7.7124` | `7.461` | `+0.57%` |
| `ETH-USDT` | `2359.41` | `2371.37` | `2317.6` | `+1.80%` |
| `LINK-USDT` | `11.5198` | `11.6491` | `11.2628` | `+0.92%` |
| `LTC-USDT` | `57.25` | `57.33` | `55.9` | `+2.21%` |
| `QTUM-USDT` | `0.825` | `0.856` | `0.82` | `+0.60%` |
| `SHIB-USDT` | `0.000004894` | `0.000004957` | `0.000004806` | `+1.17%` |
| `SOL-USDT` | `102` | `102.75` | `100.28` | `+1.70%` |
| `TRX-USDT` | `0.3301` | `0.3303` | `0.3288` | `+0.15%` |
| `UNI-USDT` | `6.9493` | `6.9837` | `6.6453` | `+4.42%` |
| `XLM-USDT` | `0.17` | `0.1726` | `0.1678` | `+0.47%` |
| `XMR-USDT` | `601.81` | `617` | `596.37` | `-0.29%` |
| `XRP-USDT` | `1.30594` | `1.31573` | `1.27508` | `+2.40%` |

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
    "lastUpdated": "2026-10-25 17:44:13 UTC"
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

