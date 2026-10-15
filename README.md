# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-15 19:57:00 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2313` | `0.2323` | `0.2161` | `+1.26%` |
| `ALGO-USDT` | `0.115` | `0.1163` | `0.1073` | `-0.17%` |
| `ATOM-USDT` | `1.7588` | `1.7769` | `1.649` | `+0.12%` |
| `AVAX-USDT` | `10.051` | `10.088` | `9.348` | `+1.77%` |
| `BCH-USDT` | `279.84` | `280.14` | `256.87` | `+3.88%` |
| `BTC-USDT` | `82387.7` | `82626.9` | `79800.9` | `+0.73%` |
| `CAKE-USDT` | `2.219` | `2.262` | `2.136` | `-0.58%` |
| `DASH-USDT` | `49.64` | `50.05` | `45.95` | `+1.43%` |
| `DGB-USDT` | `0.003459` | `0.00359` | `0.003372` | `-0.43%` |
| `DOGE-USDT` | `0.08157` | `0.0823` | `0.07773` | `-0.45%` |
| `DOT-USDT` | `1.1313` | `1.1581` | `1.0496` | `-0.11%` |
| `ETC-USDT` | `8.0754` | `8.0754` | `7.4944` | `+1.41%` |
| `ETH-USDT` | `2453.1` | `2462.22` | `2317` | `+0.96%` |
| `LINK-USDT` | `12.5589` | `12.6057` | `11.8239` | `+0.97%` |
| `LTC-USDT` | `60.54` | `60.78` | `57.22` | `+1.35%` |
| `QTUM-USDT` | `0.924` | `0.93` | `0.865` | `-0.64%` |
| `SHIB-USDT` | `0.000005127` | `0.000005133` | `0.000004826` | `+1.28%` |
| `SOL-USDT` | `105.96` | `106.51` | `100.6` | `+1.66%` |
| `TRX-USDT` | `0.3326` | `0.3336` | `0.3293` | `-0.26%` |
| `UNI-USDT` | `7.4261` | `7.6351` | `6.7851` | `+4.55%` |
| `XLM-USDT` | `0.1853` | `0.1863` | `0.1764` | `+0.81%` |
| `XMR-USDT` | `543.4` | `555.88` | `527.49` | `-0.67%` |
| `XRP-USDT` | `1.34308` | `1.34756` | `1.28377` | `+1.32%` |

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
    "lastUpdated": "2026-10-15 19:57:00 UTC"
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

