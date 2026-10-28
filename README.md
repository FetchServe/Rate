# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-28 01:57:39 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2072` | `0.2072` | `0.2013` | `+0.97%` |
| `ALGO-USDT` | `0.1043` | `0.105` | `0.1018` | `-0.47%` |
| `ATOM-USDT` | `1.644` | `1.646` | `1.6048` | `+0.93%` |
| `AVAX-USDT` | `9.029` | `9.037` | `8.667` | `+1.38%` |
| `BCH-USDT` | `294.25` | `297.83` | `277.23` | `+4.03%` |
| `BTC-USDT` | `80966.3` | `81286.9` | `79509.3` | `+1.10%` |
| `CAKE-USDT` | `2.084` | `2.14` | `2.042` | `-2.61%` |
| `DASH-USDT` | `55.25` | `55.86` | `53.72` | `+2.29%` |
| `DGB-USDT` | `0.003375` | `0.00345` | `0.003216` | `-1.22%` |
| `DOGE-USDT` | `0.07934` | `0.07939` | `0.07668` | `+1.92%` |
| `DOT-USDT` | `1.0084` | `1.0084` | `0.9775` | `+0.90%` |
| `ETC-USDT` | `7.6779` | `7.6783` | `7.471` | `+1.11%` |
| `ETH-USDT` | `2356.54` | `2364.16` | `2297.79` | `+1.44%` |
| `LINK-USDT` | `11.6638` | `11.6638` | `11.2288` | `+2.91%` |
| `LTC-USDT` | `57.45` | `57.47` | `55.74` | `+1.44%` |
| `QTUM-USDT` | `0.839` | `0.839` | `0.808` | `+2.19%` |
| `SHIB-USDT` | `0.000004948` | `0.000004958` | `0.000004798` | `+1.66%` |
| `SOL-USDT` | `101.8` | `101.88` | `99.17` | `+1.13%` |
| `TRX-USDT` | `0.3316` | `0.3324` | `0.3273` | `+0.54%` |
| `UNI-USDT` | `7.1401` | `7.1946` | `6.9453` | `+0.15%` |
| `XLM-USDT` | `0.1725` | `0.1725` | `0.1665` | `+1.95%` |
| `XMR-USDT` | `601.76` | `613.23` | `585.65` | `-0.98%` |
| `XRP-USDT` | `1.33916` | `1.33917` | `1.29114` | `+2.69%` |

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
    "lastUpdated": "2026-10-28 01:57:39 UTC"
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

