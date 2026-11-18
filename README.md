# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-18 08:46:04 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1551` | `0.1565` | `0.1493` | `+1.37%` |
| `ALGO-USDT` | `0.0797` | `0.0806` | `0.0773` | `-0.37%` |
| `ATOM-USDT` | `1.3086` | `1.3795` | `1.2995` | `-1.43%` |
| `AVAX-USDT` | `7.166` | `7.314` | `6.959` | `+0.09%` |
| `BCH-USDT` | `209.44` | `213.75` | `204.58` | `+0.00%` |
| `BTC-USDT` | `64794` | `65437.6` | `63352` | `+0.54%` |
| `CAKE-USDT` | `1.64` | `1.662` | `1.597` | `+0.36%` |
| `DASH-USDT` | `37.99` | `38.95` | `36.99` | `+0.79%` |
| `DGB-USDT` | `0.002687` | `0.003035` | `0.002629` | `+1.66%` |
| `DOGE-USDT` | `0.05977` | `0.06044` | `0.05742` | `+1.61%` |
| `DOT-USDT` | `0.7329` | `0.7479` | `0.7131` | `+0.15%` |
| `ETC-USDT` | `6.0058` | `6.0451` | `5.7613` | `+2.62%` |
| `ETH-USDT` | `1814.9` | `1835.94` | `1751.41` | `-0.44%` |
| `LINK-USDT` | `9.2597` | `9.4103` | `8.9394` | `+1.13%` |
| `LTC-USDT` | `44.71` | `45.43` | `43.73` | `+0.06%` |
| `QTUM-USDT` | `0.661` | `0.67` | `0.652` | `+1.22%` |
| `SHIB-USDT` | `0.000003865` | `0.000003911` | `0.000003748` | `+0.59%` |
| `SOL-USDT` | `74.91` | `75.77` | `71.07` | `+3.35%` |
| `TRX-USDT` | `0.3088` | `0.3102` | `0.3053` | `+1.04%` |
| `UNI-USDT` | `5.2548` | `5.456` | `5.1647` | `-1.06%` |
| `XLM-USDT` | `0.142` | `0.1427` | `0.1358` | `+3.42%` |
| `XMR-USDT` | `504.55` | `524` | `493.33` | `-1.07%` |
| `XRP-USDT` | `1.00268` | `1.00776` | `0.94548` | `+4.66%` |

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
    "lastUpdated": "2026-11-18 08:46:04 UTC"
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

