# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-14 10:58:05 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2349` | `0.2394` | `0.2316` | `+0.77%` |
| `ALGO-USDT` | `0.1203` | `0.123` | `0.1162` | `+2.73%` |
| `ATOM-USDT` | `1.8028` | `1.9012` | `1.7831` | `-0.57%` |
| `AVAX-USDT` | `10.218` | `10.424` | `10.143` | `-0.30%` |
| `BCH-USDT` | `278.67` | `282.6` | `267.42` | `+3.08%` |
| `BTC-USDT` | `83414.9` | `84126.6` | `82992.7` | `+0.17%` |
| `CAKE-USDT` | `2.3` | `2.408` | `2.199` | `+0.92%` |
| `DASH-USDT` | `50.04` | `50.99` | `48.59` | `+1.27%` |
| `DGB-USDT` | `0.003478` | `0.00374` | `0.003434` | `+0.23%` |
| `DOGE-USDT` | `0.08431` | `0.08565` | `0.08304` | `+0.74%` |
| `DOT-USDT` | `1.1394` | `1.2086` | `1.1306` | `-3.01%` |
| `ETC-USDT` | `8.1249` | `8.2117` | `8.0122` | `+0.71%` |
| `ETH-USDT` | `2505.45` | `2529.84` | `2479.2` | `+0.28%` |
| `LINK-USDT` | `12.9156` | `13.1` | `12.7269` | `+0.43%` |
| `LTC-USDT` | `61.62` | `62.42` | `60.45` | `+1.08%` |
| `QTUM-USDT` | `0.931` | `0.951` | `0.918` | `+0.43%` |
| `SHIB-USDT` | `0.000005148` | `0.000005244` | `0.00000512` | `-0.36%` |
| `SOL-USDT` | `107.09` | `108.65` | `105.65` | `+0.64%` |
| `TRX-USDT` | `0.3333` | `0.3342` | `0.3261` | `+1.24%` |
| `UNI-USDT` | `7.355` | `7.675` | `7.2249` | `+0.33%` |
| `XLM-USDT` | `0.1893` | `0.1934` | `0.1883` | `-0.99%` |
| `XMR-USDT` | `553.04` | `558.1` | `526.2` | `+3.58%` |
| `XRP-USDT` | `1.37296` | `1.38661` | `1.34972` | `+1.04%` |

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
    "lastUpdated": "2026-10-14 10:58:05 UTC"
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

