# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-15 22:53:00 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.231` | `0.2323` | `0.2161` | `+0.69%` |
| `ALGO-USDT` | `0.1181` | `0.1184` | `0.1073` | `+1.98%` |
| `ATOM-USDT` | `1.7489` | `1.7769` | `1.649` | `-1.00%` |
| `AVAX-USDT` | `10.06` | `10.088` | `9.348` | `+0.18%` |
| `BCH-USDT` | `278.43` | `280.14` | `256.87` | `+3.73%` |
| `BTC-USDT` | `82471.5` | `82626.9` | `79800.9` | `+1.00%` |
| `CAKE-USDT` | `2.207` | `2.262` | `2.136` | `-0.85%` |
| `DASH-USDT` | `49.66` | `50.05` | `45.95` | `+1.38%` |
| `DGB-USDT` | `0.00348` | `0.00359` | `0.003372` | `+0.17%` |
| `DOGE-USDT` | `0.0815` | `0.08218` | `0.07773` | `-0.64%` |
| `DOT-USDT` | `1.1545` | `1.1657` | `1.0496` | `+0.73%` |
| `ETC-USDT` | `8.0237` | `8.0895` | `7.4944` | `+0.44%` |
| `ETH-USDT` | `2456.94` | `2467.07` | `2317` | `+1.56%` |
| `LINK-USDT` | `12.5216` | `12.6057` | `11.8239` | `+0.87%` |
| `LTC-USDT` | `60.75` | `60.93` | `57.22` | `+2.01%` |
| `QTUM-USDT` | `0.924` | `0.927` | `0.865` | `-0.32%` |
| `SHIB-USDT` | `0.000005137` | `0.000005154` | `0.000004826` | `+1.04%` |
| `SOL-USDT` | `105.88` | `106.51` | `100.6` | `+1.15%` |
| `TRX-USDT` | `0.3324` | `0.3333` | `0.3293` | `+0.06%` |
| `UNI-USDT` | `7.4688` | `7.6351` | `6.7851` | `+4.53%` |
| `XLM-USDT` | `0.1838` | `0.1863` | `0.1764` | `-0.05%` |
| `XMR-USDT` | `546.43` | `555.52` | `527.49` | `-1.44%` |
| `XRP-USDT` | `1.34053` | `1.34756` | `1.28377` | `+0.53%` |

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
    "lastUpdated": "2026-10-15 22:53:00 UTC"
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

