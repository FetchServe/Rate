# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-16 10:00:19 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2312` | `0.2323` | `0.2177` | `+3.63%` |
| `ALGO-USDT` | `0.1196` | `0.122` | `0.108` | `+9.32%` |
| `ATOM-USDT` | `1.7712` | `1.7793` | `1.649` | `+5.98%` |
| `AVAX-USDT` | `10.399` | `10.414` | `9.473` | `+7.96%` |
| `BCH-USDT` | `283.1` | `284.02` | `261.27` | `+6.81%` |
| `BTC-USDT` | `82018.5` | `82626.9` | `79800.9` | `+0.91%` |
| `CAKE-USDT` | `2.203` | `2.262` | `2.165` | `-0.13%` |
| `DASH-USDT` | `50.17` | `50.45` | `46.46` | `+4.60%` |
| `DGB-USDT` | `0.00356` | `0.003621` | `0.003372` | `+4.46%` |
| `DOGE-USDT` | `0.0823` | `0.08261` | `0.07788` | `+2.60%` |
| `DOT-USDT` | `1.1459` | `1.1867` | `1.0496` | `+4.47%` |
| `ETC-USDT` | `8.0975` | `8.1169` | `7.6485` | `+4.95%` |
| `ETH-USDT` | `2449.63` | `2467.07` | `2324.44` | `+3.11%` |
| `LINK-USDT` | `12.6367` | `12.6705` | `11.8239` | `+4.31%` |
| `LTC-USDT` | `61.05` | `61.88` | `57.83` | `+4.26%` |
| `QTUM-USDT` | `0.915` | `0.924` | `0.873` | `+3.62%` |
| `SHIB-USDT` | `0.000005158` | `0.00000517` | `0.000004912` | `+3.74%` |
| `SOL-USDT` | `106.24` | `107` | `100.91` | `+2.95%` |
| `TRX-USDT` | `0.336` | `0.3364` | `0.3293` | `+1.29%` |
| `UNI-USDT` | `7.4161` | `7.6351` | `6.8245` | `+6.49%` |
| `XLM-USDT` | `0.1842` | `0.1863` | `0.1772` | `+1.82%` |
| `XMR-USDT` | `562.34` | `571.22` | `527.49` | `+3.69%` |
| `XRP-USDT` | `1.33709` | `1.34756` | `1.28377` | `+1.35%` |

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
    "lastUpdated": "2026-10-16 10:00:19 UTC"
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

