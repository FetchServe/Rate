# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-19 14:35:20 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1553` | `0.1559` | `0.1482` | `+1.17%` |
| `ALGO-USDT` | `0.0785` | `0.079` | `0.0748` | `+0.25%` |
| `ATOM-USDT` | `1.3011` | `1.3249` | `1.2721` | `+1.27%` |
| `AVAX-USDT` | `7.144` | `7.176` | `6.852` | `+1.11%` |
| `BCH-USDT` | `209.55` | `210.8` | `203.13` | `+0.83%` |
| `BTC-USDT` | `63880.5` | `64073.8` | `62068.9` | `+0.39%` |
| `CAKE-USDT` | `1.619` | `1.628` | `1.555` | `+0.93%` |
| `DASH-USDT` | `37.76` | `38.05` | `36.3` | `+0.53%` |
| `DGB-USDT` | `0.002674` | `0.002815` | `0.002509` | `-0.96%` |
| `DOGE-USDT` | `0.05966` | `0.05986` | `0.0577` | `+0.74%` |
| `DOT-USDT` | `0.723` | `0.7259` | `0.7022` | `-0.20%` |
| `ETC-USDT` | `5.942` | `5.9881` | `5.8089` | `-0.69%` |
| `ETH-USDT` | `1808.56` | `1817.32` | `1733.13` | `+1.45%` |
| `LINK-USDT` | `9.2256` | `9.2786` | `8.8881` | `+1.25%` |
| `LTC-USDT` | `44.41` | `44.82` | `43.11` | `+0.33%` |
| `QTUM-USDT` | `0.658` | `0.67` | `0.654` | `-1.79%` |
| `SHIB-USDT` | `0.000003902` | `0.000003918` | `0.000003739` | `+1.90%` |
| `SOL-USDT` | `75.37` | `75.45` | `72.23` | `+1.53%` |
| `TRX-USDT` | `0.3125` | `0.3137` | `0.3084` | `+0.87%` |
| `UNI-USDT` | `5.1293` | `5.2433` | `5.0535` | `-1.10%` |
| `XLM-USDT` | `0.1383` | `0.1408` | `0.135` | `-1.77%` |
| `XMR-USDT` | `502.83` | `508.2` | `487.88` | `-0.82%` |
| `XRP-USDT` | `0.99479` | `0.9961` | `0.95477` | `+0.71%` |

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
    "lastUpdated": "2026-11-19 14:35:20 UTC"
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

