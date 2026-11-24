# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-24 01:05:35 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1497` | `0.1564` | `0.1419` | `+4.46%` |
| `ALGO-USDT` | `0.0817` | `0.0879` | `0.0747` | `+9.22%` |
| `ATOM-USDT` | `1.2806` | `1.2918` | `1.1558` | `+10.19%` |
| `AVAX-USDT` | `6.823` | `7.228` | `6.567` | `+2.77%` |
| `BCH-USDT` | `202.4` | `212.88` | `194.07` | `+2.13%` |
| `BTC-USDT` | `61414.9` | `64600` | `60387.7` | `+0.58%` |
| `CAKE-USDT` | `1.588` | `1.638` | `1.5` | `+4.47%` |
| `DASH-USDT` | `35.68` | `37.95` | `34.98` | `+1.16%` |
| `DGB-USDT` | `0.002645` | `0.00284` | `0.002561` | `+1.69%` |
| `DOGE-USDT` | `0.05674` | `0.06024` | `0.05437` | `+3.25%` |
| `DOT-USDT` | `0.68` | `0.7234` | `0.6497` | `+3.73%` |
| `ETC-USDT` | `5.9081` | `6.0815` | `5.6632` | `+3.80%` |
| `ETH-USDT` | `1716.52` | `1847.32` | `1696.63` | `+0.14%` |
| `LINK-USDT` | `9.0864` | `9.56` | `8.7179` | `+2.82%` |
| `LTC-USDT` | `41.67` | `43.68` | `39.62` | `+4.51%` |
| `QTUM-USDT` | `0.632` | `0.655` | `0.605` | `+3.94%` |
| `SHIB-USDT` | `0.000003663` | `0.00000387` | `0.000003548` | `+2.37%` |
| `SOL-USDT` | `72.35` | `78.48` | `69.9` | `+2.50%` |
| `TRX-USDT` | `0.311` | `0.3125` | `0.3039` | `+1.83%` |
| `UNI-USDT` | `4.8849` | `5.3104` | `4.6321` | `+4.26%` |
| `XLM-USDT` | `0.1314` | `0.1384` | `0.1254` | `+3.62%` |
| `XMR-USDT` | `483.08` | `520.15` | `480.88` | `-1.88%` |
| `XRP-USDT` | `0.9456` | `1.02635` | `0.91318` | `+2.63%` |

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
    "lastUpdated": "2026-11-24 01:05:35 UTC"
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

