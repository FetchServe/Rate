# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-22 21:44:00 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.225` | `0.2586` | `0.2066` | `+0.85%` |
| `ALGO-USDT` | `0.0918` | `0.1049` | `0.0911` | `-4.47%` |
| `ATOM-USDT` | `1.5685` | `1.72` | `1.5` | `-1.07%` |
| `AVAX-USDT` | `7.47` | `8.316` | `7.012` | `-3.37%` |
| `BCH-USDT` | `273.85` | `305.27` | `262.07` | `-5.13%` |
| `BTC-USDT` | `76938.9` | `78816.1` | `76486.5` | `-1.61%` |
| `CAKE-USDT` | `1.702` | `1.855` | `1.681` | `-3.46%` |
| `DASH-USDT` | `40.56` | `47.52` | `36` | `+6.82%` |
| `DGB-USDT` | `0.00436` | `0.004566` | `0.004001` | `-2.59%` |
| `DOGE-USDT` | `0.09248` | `0.10089` | `0.08308` | `+1.83%` |
| `DOT-USDT` | `0.9105` | `1.032` | `0.9002` | `-0.87%` |
| `ETC-USDT` | `7.8254` | `9.0904` | `7.2996` | `-0.91%` |
| `ETH-USDT` | `2413.03` | `2547.38` | `2385.56` | `-2.81%` |
| `LINK-USDT` | `11.5212` | `12.604` | `10.9` | `-4.32%` |
| `LTC-USDT` | `52.18` | `55.42` | `50.18` | `-0.89%` |
| `QTUM-USDT` | `0.854` | `0.927` | `0.819` | `+3.76%` |
| `RVN-USDT` | `0.00326` | `0.00376` | `0.00326` | `-3.83%` |
| `SHIB-USDT` | `0.000005428` | `0.000006223` | `0.00000522` | `-3.48%` |
| `SOL-USDT` | `93.11` | `102.72` | `87.75` | `+0.16%` |
| `TRX-USDT` | `0.345` | `0.3505` | `0.3387` | `+0.99%` |
| `UNI-USDT` | `4.2683` | `4.4464` | `3.738` | `+3.67%` |
| `XLM-USDT` | `0.1946` | `0.2225` | `0.1887` | `-0.86%` |
| `XMR-USDT` | `427.33` | `465.88` | `403.85` | `+3.44%` |
| `XRP-USDT` | `1.45969` | `1.69945` | `1.37734` | `+3.86%` |

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
    "lastUpdated": "2026-08-22 21:44:00 UTC"
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

