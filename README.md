# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-16 00:55:31 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2303` | `0.2323` | `0.2161` | `+0.56%` |
| `ALGO-USDT` | `0.118` | `0.1193` | `0.1073` | `+2.07%` |
| `ATOM-USDT` | `1.7439` | `1.7623` | `1.649` | `-0.32%` |
| `AVAX-USDT` | `10.04` | `10.088` | `9.348` | `+0.92%` |
| `BCH-USDT` | `278.88` | `280.14` | `256.87` | `+3.64%` |
| `BTC-USDT` | `82300.1` | `82626.9` | `79800.9` | `+0.87%` |
| `CAKE-USDT` | `2.207` | `2.262` | `2.136` | `-1.16%` |
| `DASH-USDT` | `49.71` | `50.05` | `45.95` | `+1.44%` |
| `DGB-USDT` | `0.00346` | `0.003536` | `0.003372` | `+0.37%` |
| `DOGE-USDT` | `0.08126` | `0.082` | `0.07773` | `-0.47%` |
| `DOT-USDT` | `1.1532` | `1.1657` | `1.0496` | `+0.73%` |
| `ETC-USDT` | `8.0072` | `8.0895` | `7.4944` | `+1.02%` |
| `ETH-USDT` | `2441.04` | `2467.07` | `2317` | `+0.91%` |
| `LINK-USDT` | `12.481` | `12.6057` | `11.8239` | `+0.37%` |
| `LTC-USDT` | `61.18` | `61.88` | `57.22` | `+3.27%` |
| `QTUM-USDT` | `0.912` | `0.924` | `0.865` | `-0.86%` |
| `SHIB-USDT` | `0.000005131` | `0.000005154` | `0.000004826` | `+1.20%` |
| `SOL-USDT` | `105.51` | `106.51` | `100.6` | `+1.19%` |
| `TRX-USDT` | `0.3335` | `0.3337` | `0.3293` | `+0.33%` |
| `UNI-USDT` | `7.4794` | `7.6351` | `6.7851` | `+4.34%` |
| `XLM-USDT` | `0.1833` | `0.1863` | `0.1764` | `+0.49%` |
| `XMR-USDT` | `555.1` | `555.52` | `527.49` | `+0.12%` |
| `XRP-USDT` | `1.33547` | `1.34756` | `1.28377` | `+0.69%` |

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
    "lastUpdated": "2026-10-16 00:55:31 UTC"
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

