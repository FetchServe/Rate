# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-10 15:29:11 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2552` | `0.2594` | `0.2353` | `+7.99%` |
| `ALGO-USDT` | `0.118` | `0.1188` | `0.1097` | `+1.98%` |
| `ATOM-USDT` | `1.9572` | `2.0847` | `1.917` | `-0.08%` |
| `AVAX-USDT` | `10.521` | `10.674` | `10.117` | `+3.63%` |
| `BCH-USDT` | `280.59` | `281.69` | `273.01` | `+2.48%` |
| `BTC-USDT` | `82974.6` | `83066.1` | `82282.5` | `+0.05%` |
| `CAKE-USDT` | `2.195` | `2.233` | `2.164` | `+0.45%` |
| `DASH-USDT` | `51.46` | `51.95` | `50.74` | `+0.52%` |
| `DGB-USDT` | `0.00366` | `0.003712` | `0.003369` | `-1.05%` |
| `DOGE-USDT` | `0.0862` | `0.08671` | `0.08422` | `+2.15%` |
| `DOT-USDT` | `1.2546` | `1.2965` | `1.1651` | `+7.61%` |
| `ETC-USDT` | `8.3588` | `8.5209` | `8.2238` | `+1.64%` |
| `ETH-USDT` | `2508.51` | `2517.38` | `2474.56` | `+0.83%` |
| `LINK-USDT` | `13.1471` | `13.25` | `12.6371` | `+2.82%` |
| `LTC-USDT` | `64.04` | `64.23` | `63.16` | `+1.32%` |
| `QTUM-USDT` | `1.013` | `1.013` | `0.93` | `+8.92%` |
| `SHIB-USDT` | `0.000005454` | `0.000005522` | `0.000005355` | `+1.75%` |
| `SOL-USDT` | `110.49` | `110.77` | `108.44` | `+0.95%` |
| `TRX-USDT` | `0.3313` | `0.333` | `0.3306` | `-0.39%` |
| `UNI-USDT` | `7.6315` | `7.71` | `7.2298` | `+3.95%` |
| `XLM-USDT` | `0.1981` | `0.1986` | `0.1914` | `+3.12%` |
| `XMR-USDT` | `526.28` | `538.53` | `514.52` | `-2.15%` |
| `XRP-USDT` | `1.407` | `1.41299` | `1.37902` | `+1.95%` |

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
    "lastUpdated": "2026-10-10 15:29:11 UTC"
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

