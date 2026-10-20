# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-20 15:30:52 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2211` | `0.2267` | `0.2148` | `+0.86%` |
| `ALGO-USDT` | `0.1116` | `0.1142` | `0.1079` | `+1.27%` |
| `ATOM-USDT` | `1.7456` | `1.792` | `1.71` | `-2.02%` |
| `AVAX-USDT` | `9.613` | `9.918` | `9.391` | `-0.66%` |
| `BCH-USDT` | `277.08` | `284.17` | `272.32` | `-0.88%` |
| `BTC-USDT` | `82545.9` | `83440.7` | `81205.2` | `+0.18%` |
| `CAKE-USDT` | `2.2` | `2.225` | `2.155` | `+0.82%` |
| `DASH-USDT` | `49.88` | `51.88` | `48.91` | `+0.80%` |
| `DGB-USDT` | `0.003381` | `0.003522` | `0.00327` | `+1.22%` |
| `DOGE-USDT` | `0.08041` | `0.08201` | `0.0785` | `+0.80%` |
| `DOT-USDT` | `1.1524` | `1.1877` | `1.126` | `-1.15%` |
| `ETC-USDT` | `7.8309` | `8.0026` | `7.6665` | `+0.63%` |
| `ETH-USDT` | `2434.52` | `2477.89` | `2372.87` | `+0.79%` |
| `LINK-USDT` | `12.1548` | `12.4707` | `11.8381` | `+0.67%` |
| `LTC-USDT` | `59.69` | `60.99` | `58.29` | `-0.63%` |
| `QTUM-USDT` | `0.874` | `0.878` | `0.85` | `+2.58%` |
| `SHIB-USDT` | `0.000005075` | `0.000005151` | `0.000004946` | `+1.05%` |
| `SOL-USDT` | `105.42` | `108.23` | `103.65` | `+0.42%` |
| `TRX-USDT` | `0.3313` | `0.3328` | `0.3306` | `-0.24%` |
| `UNI-USDT` | `7.2786` | `7.5695` | `7.0964` | `-1.31%` |
| `XLM-USDT` | `0.1787` | `0.1824` | `0.175` | `+0.84%` |
| `XMR-USDT` | `623.82` | `627.4` | `583.79` | `+3.22%` |
| `XRP-USDT` | `1.31642` | `1.3462` | `1.28593` | `+0.57%` |

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
    "lastUpdated": "2026-10-20 15:30:52 UTC"
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

