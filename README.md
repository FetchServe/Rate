# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-10 02:30:25 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2548` | `0.2559` | `0.2327` | `+9.49%` |
| `ALGO-USDT` | `0.1156` | `0.1209` | `0.1097` | `-1.61%` |
| `ATOM-USDT` | `2.0284` | `2.0847` | `1.8066` | `+12.14%` |
| `AVAX-USDT` | `10.42` | `10.502` | `10.115` | `+2.15%` |
| `BCH-USDT` | `278.94` | `282.05` | `272.38` | `+0.61%` |
| `BTC-USDT` | `82633.1` | `83510` | `81912.1` | `+0.87%` |
| `CAKE-USDT` | `2.216` | `2.219` | `2.145` | `+3.26%` |
| `DASH-USDT` | `51.58` | `52.14` | `50.57` | `+1.75%` |
| `DGB-USDT` | `0.003501` | `0.00377` | `0.003369` | `-7.01%` |
| `DOGE-USDT` | `0.08628` | `0.0864` | `0.0839` | `+2.13%` |
| `DOT-USDT` | `1.2816` | `1.2965` | `1.1282` | `+13.52%` |
| `ETC-USDT` | `8.5` | `8.5209` | `8.0972` | `+4.95%` |
| `ETH-USDT` | `2493.51` | `2520` | `2474.56` | `+0.59%` |
| `LINK-USDT` | `12.8404` | `12.9713` | `12.6371` | `+0.81%` |
| `LTC-USDT` | `63.69` | `64.53` | `63.16` | `+0.36%` |
| `QTUM-USDT` | `0.955` | `0.955` | `0.925` | `+3.24%` |
| `SHIB-USDT` | `0.000005492` | `0.000005501` | `0.000005315` | `+3.21%` |
| `SOL-USDT` | `109.74` | `112.02` | `108.44` | `+0.05%` |
| `TRX-USDT` | `0.3307` | `0.3334` | `0.3307` | `-0.51%` |
| `UNI-USDT` | `7.3565` | `7.4575` | `7.2298` | `+1.22%` |
| `XLM-USDT` | `0.1961` | `0.1965` | `0.1914` | `+1.60%` |
| `XMR-USDT` | `517.48` | `549.05` | `515` | `-4.69%` |
| `XRP-USDT` | `1.40696` | `1.41` | `1.374` | `+1.53%` |

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
    "lastUpdated": "2026-10-10 02:30:25 UTC"
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

