# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-21 06:14:45 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2222` | `0.2267` | `0.2148` | `+2.72%` |
| `ALGO-USDT` | `0.1126` | `0.1158` | `0.1092` | `+1.25%` |
| `ATOM-USDT` | `1.7344` | `1.792` | `1.71` | `-0.67%` |
| `AVAX-USDT` | `9.617` | `9.918` | `9.391` | `+0.84%` |
| `BCH-USDT` | `285.13` | `288.26` | `272.32` | `+3.02%` |
| `BTC-USDT` | `82664.4` | `83440.7` | `81322.8` | `+1.23%` |
| `CAKE-USDT` | `2.253` | `2.267` | `2.155` | `+4.16%` |
| `DASH-USDT` | `49.97` | `51.2` | `48.91` | `+0.30%` |
| `DGB-USDT` | `0.003351` | `0.003542` | `0.003274` | `+1.05%` |
| `DOGE-USDT` | `0.08142` | `0.08233` | `0.07879` | `+2.95%` |
| `DOT-USDT` | `1.1486` | `1.1877` | `1.126` | `+1.71%` |
| `ETC-USDT` | `7.9346` | `8.0026` | `7.694` | `+2.54%` |
| `ETH-USDT` | `2438.69` | `2477.89` | `2377.18` | `+1.95%` |
| `LINK-USDT` | `12.2798` | `12.4707` | `11.8886` | `+2.74%` |
| `LTC-USDT` | `61.09` | `62.18` | `58.29` | `+3.07%` |
| `QTUM-USDT` | `0.872` | `0.879` | `0.85` | `+2.22%` |
| `SHIB-USDT` | `0.000005107` | `0.000005156` | `0.000004948` | `+2.52%` |
| `SOL-USDT` | `105.71` | `108.23` | `103.76` | `+1.41%` |
| `TRX-USDT` | `0.3312` | `0.3328` | `0.3306` | `-0.21%` |
| `UNI-USDT` | `7.412` | `7.7871` | `7.0964` | `+3.93%` |
| `XLM-USDT` | `0.1821` | `0.1838` | `0.1752` | `+2.93%` |
| `XMR-USDT` | `577.29` | `627.4` | `570.32` | `-4.39%` |
| `XRP-USDT` | `1.33376` | `1.3462` | `1.29036` | `+2.56%` |

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
    "lastUpdated": "2026-10-21 06:14:45 UTC"
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

