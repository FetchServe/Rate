# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-19 22:00:01 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2271` | `0.235` | `0.2208` | `+0.84%` |
| `ALGO-USDT` | `0.1014` | `0.1028` | `0.0957` | `+2.73%` |
| `ATOM-USDT` | `1.7192` | `1.7824` | `1.6721` | `-0.56%` |
| `AVAX-USDT` | `9.687` | `9.842` | `8.178` | `+17.23%` |
| `BCH-USDT` | `251.9` | `266.09` | `245.08` | `-2.62%` |
| `BTC-USDT` | `81108` | `81936.5` | `80845.2` | `-0.16%` |
| `CAKE-USDT` | `2.385` | `2.466` | `2.372` | `-2.93%` |
| `DASH-USDT` | `58.21` | `65.09` | `57.59` | `-5.08%` |
| `DGB-USDT` | `0.00433` | `0.0044` | `0.004253` | `+1.81%` |
| `DOGE-USDT` | `0.08738` | `0.09126` | `0.08649` | `-0.92%` |
| `DOT-USDT` | `1.1106` | `1.1577` | `1.0961` | `-2.75%` |
| `ETC-USDT` | `8.4773` | `8.6155` | `8.1168` | `+3.79%` |
| `ETH-USDT` | `2628.08` | `2667.53` | `2603.41` | `+0.04%` |
| `LINK-USDT` | `12.3469` | `12.6918` | `12.0418` | `-0.25%` |
| `LTC-USDT` | `57.16` | `59.19` | `56.75` | `-0.08%` |
| `QTUM-USDT` | `0.951` | `0.97` | `0.93` | `-0.31%` |
| `RVN-USDT` | `0.00252` | `0.00259` | `0.00251` | `-0.78%` |
| `SHIB-USDT` | `0.000005477` | `0.000005696` | `0.000005373` | `-0.68%` |
| `SOL-USDT` | `110.53` | `114.07` | `110.16` | `-2.38%` |
| `TRX-USDT` | `0.3399` | `0.3399` | `0.3368` | `+0.32%` |
| `UNI-USDT` | `8.5238` | `9.4942` | `8.4547` | `-5.18%` |
| `XLM-USDT` | `0.1953` | `0.2042` | `0.191` | `+0.61%` |
| `XMR-USDT` | `539.07` | `591.47` | `536.01` | `-4.89%` |
| `XRP-USDT` | `1.40948` | `1.45377` | `1.39253` | `+0.54%` |

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
    "lastUpdated": "2026-09-19 22:00:01 UTC"
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

