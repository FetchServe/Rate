# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-10-06 02:00:09 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2679` | `0.2767` | `0.2589` | `+1.59%` |
| `ALGO-USDT` | `0.1262` | `0.1326` | `0.1259` | `-3.07%` |
| `ATOM-USDT` | `1.7958` | `1.8467` | `1.729` | `+2.66%` |
| `AVAX-USDT` | `11.155` | `11.295` | `10.8` | `+1.72%` |
| `BCH-USDT` | `315.19` | `321.84` | `312.63` | `-1.16%` |
| `BTC-USDT` | `85650.6` | `86722.6` | `84992.7` | `-1.10%` |
| `CAKE-USDT` | `2.456` | `2.55` | `2.428` | `-2.42%` |
| `DASH-USDT` | `57.6` | `61` | `57.36` | `-3.37%` |
| `DGB-USDT` | `0.004248` | `0.00432` | `0.00408` | `-1.43%` |
| `DOGE-USDT` | `0.09493` | `0.09717` | `0.0938` | `-1.25%` |
| `DOT-USDT` | `1.2192` | `1.246` | `1.184` | `+1.01%` |
| `ETC-USDT` | `8.8941` | `9.0926` | `8.8158` | `-1.42%` |
| `ETH-USDT` | `2707.46` | `2737.55` | `2679.97` | `-0.63%` |
| `LINK-USDT` | `13.8112` | `14.2808` | `13.6704` | `-2.55%` |
| `LTC-USDT` | `69.45` | `71.75` | `69.29` | `-1.23%` |
| `QTUM-USDT` | `0.987` | `1` | `0.976` | `+0.20%` |
| `RVN-USDT` | `0.00267` | `0.00298` | `0.00234` | `+12.65%` |
| `SHIB-USDT` | `0.000005842` | `0.000006009` | `0.000005838` | `-1.91%` |
| `SOL-USDT` | `120.64` | `122.07` | `118.96` | `-0.44%` |
| `TRX-USDT` | `0.336` | `0.3382` | `0.3349` | `-0.05%` |
| `UNI-USDT` | `8.9784` | `9.242` | `8.8429` | `-1.20%` |
| `XLM-USDT` | `0.2148` | `0.2263` | `0.211` | `-4.23%` |
| `XMR-USDT` | `560.81` | `563.99` | `535.08` | `+2.54%` |
| `XRP-USDT` | `1.50101` | `1.52869` | `1.48624` | `-1.27%` |

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
    "lastUpdated": "2026-10-06 02:00:09 UTC"
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

