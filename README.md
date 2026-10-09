# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-09 19:10:32 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2371` | `0.2414` | `0.2293` | `+3.31%` |
| `ALGO-USDT` | `0.1134` | `0.1209` | `0.1132` | `-4.14%` |
| `ATOM-USDT` | `2.0699` | `2.0734` | `1.6837` | `+22.39%` |
| `AVAX-USDT` | `10.187` | `10.502` | `10.012` | `+1.66%` |
| `BCH-USDT` | `274.37` | `284.82` | `268.98` | `-2.02%` |
| `BTC-USDT` | `82509.3` | `83510` | `81449.2` | `+1.28%` |
| `CAKE-USDT` | `2.178` | `2.203` | `2.124` | `+2.54%` |
| `DASH-USDT` | `51.43` | `52.14` | `50.38` | `+1.60%` |
| `DGB-USDT` | `0.00361` | `0.00377` | `0.00359` | `-1.95%` |
| `DOGE-USDT` | `0.08466` | `0.08559` | `0.08318` | `+1.77%` |
| `DOT-USDT` | `1.2083` | `1.2209` | `1.0357` | `+16.46%` |
| `ETC-USDT` | `8.27` | `8.3233` | `7.9407` | `+4.08%` |
| `ETH-USDT` | `2485.76` | `2520` | `2443.99` | `+1.70%` |
| `LINK-USDT` | `12.8246` | `12.9713` | `12.3948` | `+3.46%` |
| `LTC-USDT` | `63.45` | `64.53` | `62.19` | `+2.02%` |
| `QTUM-USDT` | `0.946` | `0.951` | `0.901` | `+4.99%` |
| `SHIB-USDT` | `0.000005402` | `0.000005426` | `0.000005216` | `+3.32%` |
| `SOL-USDT` | `109.45` | `112.02` | `108.37` | `+0.99%` |
| `TRX-USDT` | `0.3321` | `0.3334` | `0.3317` | `-0.27%` |
| `UNI-USDT` | `7.3024` | `7.4575` | `7.0137` | `+1.53%` |
| `XLM-USDT` | `0.1928` | `0.1958` | `0.1899` | `+1.52%` |
| `XMR-USDT` | `523.06` | `549.05` | `517.66` | `-0.54%` |
| `XRP-USDT` | `1.3881` | `1.4072` | `1.36124` | `+1.97%` |

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
    "lastUpdated": "2026-10-09 19:10:32 UTC"
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

