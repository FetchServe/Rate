# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-21 12:08:33 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2259` | `0.2267` | `0.2157` | `+4.39%` |
| `ALGO-USDT` | `0.1136` | `0.1158` | `0.1094` | `+3.46%` |
| `ATOM-USDT` | `1.75` | `1.792` | `1.71` | `+1.68%` |
| `AVAX-USDT` | `9.715` | `9.918` | `9.411` | `+2.96%` |
| `BCH-USDT` | `286.65` | `290.71` | `272.48` | `+4.80%` |
| `BTC-USDT` | `83531.2` | `83696.1` | `81322.8` | `+2.46%` |
| `CAKE-USDT` | `2.245` | `2.267` | `2.156` | `+3.88%` |
| `DASH-USDT` | `51.05` | `51.41` | `48.91` | `+3.97%` |
| `DGB-USDT` | `0.003407` | `0.003542` | `0.00331` | `+2.28%` |
| `DOGE-USDT` | `0.08208` | `0.08233` | `0.07901` | `+3.79%` |
| `DOT-USDT` | `1.1645` | `1.1877` | `1.1327` | `+2.49%` |
| `ETC-USDT` | `8.0806` | `8.15` | `7.7131` | `+4.76%` |
| `ETH-USDT` | `2469.7` | `2477.89` | `2381.51` | `+3.48%` |
| `LINK-USDT` | `12.3973` | `12.4707` | `11.9211` | `+3.60%` |
| `LTC-USDT` | `61.71` | `62.18` | `58.41` | `+5.36%` |
| `QTUM-USDT` | `0.883` | `0.889` | `0.85` | `+3.88%` |
| `SHIB-USDT` | `0.000005185` | `0.000005188` | `0.00000496` | `+4.40%` |
| `SOL-USDT` | `106.94` | `108.23` | `103.88` | `+2.69%` |
| `TRX-USDT` | `0.3309` | `0.3323` | `0.3304` | `-0.42%` |
| `UNI-USDT` | `7.5015` | `7.7871` | `7.1034` | `+4.96%` |
| `XLM-USDT` | `0.1844` | `0.1851` | `0.1754` | `+4.65%` |
| `XMR-USDT` | `600.29` | `627.4` | `570.32` | `-1.12%` |
| `XRP-USDT` | `1.35713` | `1.36883` | `1.29543` | `+4.51%` |

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
    "lastUpdated": "2026-10-21 12:08:33 UTC"
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

