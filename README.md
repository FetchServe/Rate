# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-04 14:59:24 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1953` | `0.1967` | `0.1828` | `+2.46%` |
| `ALGO-USDT` | `0.0999` | `0.1005` | `0.0899` | `+6.50%` |
| `ATOM-USDT` | `1.453` | `1.4608` | `1.3775` | `+1.69%` |
| `AVAX-USDT` | `8.857` | `8.911` | `8.283` | `+3.14%` |
| `BCH-USDT` | `280.64` | `281.14` | `265.4` | `+1.12%` |
| `BTC-USDT` | `79286.5` | `79668.8` | `75739.5` | `+2.46%` |
| `CAKE-USDT` | `1.941` | `1.95` | `1.821` | `+4.07%` |
| `DASH-USDT` | `47.83` | `48.13` | `44.07` | `+3.50%` |
| `DGB-USDT` | `0.003186` | `0.003186` | `0.00305` | `+4.45%` |
| `DOGE-USDT` | `0.07658` | `0.077` | `0.0723` | `+1.82%` |
| `DOT-USDT` | `0.9759` | `0.9844` | `0.907` | `+3.73%` |
| `ETC-USDT` | `7.2161` | `7.2533` | `6.8237` | `+2.31%` |
| `ETH-USDT` | `2376.19` | `2387.7` | `2226.62` | `+3.90%` |
| `LINK-USDT` | `11.5316` | `11.567` | `10.6324` | `+3.26%` |
| `LTC-USDT` | `55.88` | `56.17` | `52.11` | `+2.43%` |
| `QTUM-USDT` | `0.759` | `0.76` | `0.727` | `+0.79%` |
| `SHIB-USDT` | `0.000004737` | `0.000004753` | `0.000004479` | `+1.91%` |
| `SOL-USDT` | `95.08` | `95.65` | `89.91` | `+1.78%` |
| `TRX-USDT` | `0.3195` | `0.3243` | `0.3188` | `-0.93%` |
| `UNI-USDT` | `7.5255` | `7.5495` | `6.9428` | `+2.53%` |
| `XLM-USDT` | `0.1671` | `0.1678` | `0.1571` | `+1.27%` |
| `XMR-USDT` | `643.89` | `648` | `618.96` | `+3.16%` |
| `XRP-USDT` | `1.3143` | `1.31751` | `1.24181` | `+2.79%` |

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
    "lastUpdated": "2026-11-04 14:59:24 UTC"
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

