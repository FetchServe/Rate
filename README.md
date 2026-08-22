# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-22 21:14:24 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2273` | `0.2586` | `0.2066` | `+3.31%` |
| `ALGO-USDT` | `0.0926` | `0.1049` | `0.0911` | `-2.01%` |
| `ATOM-USDT` | `1.5813` | `1.72` | `1.5` | `+0.75%` |
| `AVAX-USDT` | `7.509` | `8.316` | `7.012` | `-2.03%` |
| `BCH-USDT` | `276.12` | `305.27` | `262.07` | `-3.81%` |
| `BTC-USDT` | `77063.8` | `78816.1` | `76486.5` | `-0.85%` |
| `CAKE-USDT` | `1.712` | `1.855` | `1.681` | `-2.05%` |
| `DASH-USDT` | `41.07` | `47.52` | `36` | `+13.57%` |
| `DGB-USDT` | `0.00431` | `0.004566` | `0.004001` | `-3.60%` |
| `DOGE-USDT` | `0.09357` | `0.10089` | `0.08308` | `+6.10%` |
| `DOT-USDT` | `0.9238` | `1.032` | `0.9002` | `+1.46%` |
| `ETC-USDT` | `7.849` | `9.0904` | `7.2996` | `+1.40%` |
| `ETH-USDT` | `2415.21` | `2547.38` | `2385.56` | `-1.53%` |
| `LINK-USDT` | `11.5813` | `12.604` | `10.9` | `-2.68%` |
| `LTC-USDT` | `52.53` | `55.42` | `50.18` | `+0.43%` |
| `QTUM-USDT` | `0.854` | `0.927` | `0.819` | `+3.76%` |
| `RVN-USDT` | `0.00329` | `0.00376` | `0.00329` | `-2.08%` |
| `SHIB-USDT` | `0.000005494` | `0.000006223` | `0.00000522` | `+0.91%` |
| `SOL-USDT` | `93.6` | `102.72` | `87.75` | `+1.48%` |
| `TRX-USDT` | `0.3452` | `0.3505` | `0.3387` | `+1.17%` |
| `UNI-USDT` | `4.3137` | `4.4464` | `3.738` | `+6.22%` |
| `XLM-USDT` | `0.1964` | `0.2225` | `0.1887` | `+0.66%` |
| `XMR-USDT` | `428.49` | `465.88` | `403.85` | `+4.00%` |
| `XRP-USDT` | `1.48414` | `1.69945` | `1.37734` | `+6.98%` |

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
    "lastUpdated": "2026-08-22 21:14:24 UTC"
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

