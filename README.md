# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-28 07:57:49 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2065` | `0.2087` | `0.2013` | `+1.02%` |
| `ALGO-USDT` | `0.1034` | `0.1049` | `0.1018` | `-0.19%` |
| `ATOM-USDT` | `1.631` | `1.658` | `1.6048` | `-0.12%` |
| `AVAX-USDT` | `9.007` | `9.084` | `8.694` | `+2.25%` |
| `BCH-USDT` | `298.28` | `299.89` | `279.77` | `+5.58%` |
| `BTC-USDT` | `81041.2` | `81286.9` | `79509.3` | `+1.49%` |
| `CAKE-USDT` | `2.081` | `2.126` | `2.042` | `-1.88%` |
| `DASH-USDT` | `54.35` | `55.83` | `53.72` | `-2.56%` |
| `DGB-USDT` | `0.003359` | `0.00345` | `0.003274` | `+1.02%` |
| `DOGE-USDT` | `0.08006` | `0.08033` | `0.07668` | `+3.24%` |
| `DOT-USDT` | `1.0011` | `1.0121` | `0.9775` | `+0.24%` |
| `ETC-USDT` | `7.6428` | `7.731` | `7.471` | `+0.96%` |
| `ETH-USDT` | `2358.83` | `2368.68` | `2297.79` | `+1.84%` |
| `LINK-USDT` | `11.7757` | `11.8249` | `11.2288` | `+3.44%` |
| `LTC-USDT` | `57.61` | `57.77` | `55.74` | `+1.89%` |
| `QTUM-USDT` | `0.832` | `0.843` | `0.808` | `+1.83%` |
| `SHIB-USDT` | `0.000004971` | `0.000004997` | `0.000004798` | `+2.57%` |
| `SOL-USDT` | `102.24` | `102.43` | `99.17` | `+2.11%` |
| `TRX-USDT` | `0.3314` | `0.3326` | `0.3273` | `+0.94%` |
| `UNI-USDT` | `7.1734` | `7.2316` | `6.9453` | `+1.47%` |
| `XLM-USDT` | `0.1719` | `0.1728` | `0.1665` | `+2.19%` |
| `XMR-USDT` | `611.83` | `620` | `585.65` | `+2.28%` |
| `XRP-USDT` | `1.32864` | `1.34406` | `1.29114` | `+1.90%` |

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
    "lastUpdated": "2026-10-28 07:57:49 UTC"
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

