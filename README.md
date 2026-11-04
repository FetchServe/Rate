# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-04 06:47:34 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1904` | `0.1926` | `0.1828` | `+1.92%` |
| `ALGO-USDT` | `0.0938` | `0.0949` | `0.0899` | `+3.30%` |
| `ATOM-USDT` | `1.4238` | `1.4486` | `1.3775` | `+0.18%` |
| `AVAX-USDT` | `8.571` | `8.692` | `8.283` | `+3.11%` |
| `BCH-USDT` | `274.65` | `278.67` | `265.4` | `+0.12%` |
| `BTC-USDT` | `77931.9` | `78160.4` | `75739.5` | `+1.73%` |
| `CAKE-USDT` | `1.901` | `1.914` | `1.82` | `+3.82%` |
| `DASH-USDT` | `46.47` | `46.83` | `44.07` | `+2.13%` |
| `DGB-USDT` | `0.003106` | `0.00315` | `0.00305` | `-0.28%` |
| `DOGE-USDT` | `0.07471` | `0.07575` | `0.0723` | `+1.49%` |
| `DOT-USDT` | `0.9443` | `0.9501` | `0.907` | `+1.40%` |
| `ETC-USDT` | `7.0656` | `7.1028` | `6.8237` | `+2.36%` |
| `ETH-USDT` | `2295.03` | `2308` | `2226.62` | `+2.14%` |
| `LINK-USDT` | `11.0518` | `11.3086` | `10.6324` | `+0.04%` |
| `LTC-USDT` | `54.23` | `55.16` | `52.11` | `+1.13%` |
| `QTUM-USDT` | `0.742` | `0.768` | `0.727` | `+0.67%` |
| `SHIB-USDT` | `0.000004651` | `0.000004657` | `0.000004479` | `+2.58%` |
| `SOL-USDT` | `92.92` | `93.94` | `89.91` | `+1.42%` |
| `TRX-USDT` | `0.3223` | `0.3243` | `0.3202` | `+0.43%` |
| `UNI-USDT` | `7.3749` | `7.4038` | `6.9428` | `+5.69%` |
| `XLM-USDT` | `0.163` | `0.167` | `0.1571` | `+1.24%` |
| `XMR-USDT` | `641.12` | `644.79` | `608.36` | `+5.38%` |
| `XRP-USDT` | `1.27568` | `1.29114` | `1.24181` | `+2.16%` |

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
    "lastUpdated": "2026-11-04 06:47:34 UTC"
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

