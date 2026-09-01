# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-01 11:52:47 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2004` | `0.203` | `0.1937` | `+2.08%` |
| `ALGO-USDT` | `0.0903` | `0.0911` | `0.0842` | `+5.98%` |
| `ATOM-USDT` | `1.4956` | `1.5134` | `1.4569` | `+2.03%` |
| `AVAX-USDT` | `7.286` | `7.335` | `7.134` | `+1.36%` |
| `BCH-USDT` | `249.25` | `251.75` | `243.9` | `+0.84%` |
| `BTC-USDT` | `78182.4` | `79246.9` | `77703.4` | `-0.18%` |
| `CAKE-USDT` | `1.845` | `1.905` | `1.826` | `-1.38%` |
| `DASH-USDT` | `46.13` | `48.5` | `42.8` | `+4.03%` |
| `DGB-USDT` | `0.004652` | `0.00484` | `0.004597` | `-1.85%` |
| `DOGE-USDT` | `0.08326` | `0.08395` | `0.08203` | `+0.67%` |
| `DOT-USDT` | `0.871` | `0.8764` | `0.82` | `+5.39%` |
| `ETC-USDT` | `7.3275` | `7.6` | `7.1983` | `+1.11%` |
| `ETH-USDT` | `2463.28` | `2490` | `2437.39` | `+0.70%` |
| `LINK-USDT` | `11.4904` | `11.5204` | `11.1597` | `+2.07%` |
| `LTC-USDT` | `49.12` | `49.16` | `48.11` | `+1.42%` |
| `QTUM-USDT` | `0.825` | `0.837` | `0.807` | `+1.35%` |
| `RVN-USDT` | `0.00295` | `0.003` | `0.00291` | `-0.67%` |
| `SHIB-USDT` | `0.000005199` | `0.000005223` | `0.000004995` | `+3.03%` |
| `SOL-USDT` | `102.44` | `104.98` | `101.81` | `-0.99%` |
| `TRX-USDT` | `0.3291` | `0.3351` | `0.3281` | `-1.61%` |
| `UNI-USDT` | `5.9419` | `5.9447` | `5.0478` | `+16.25%` |
| `XLM-USDT` | `0.1788` | `0.1799` | `0.1746` | `+1.36%` |
| `XMR-USDT` | `524.68` | `543.42` | `501` | `-2.63%` |
| `XRP-USDT` | `1.38616` | `1.39645` | `1.35744` | `+0.95%` |

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
    "lastUpdated": "2026-09-01 11:52:47 UTC"
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

