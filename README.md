# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-01 10:56:34 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1937` | `0.1945` | `0.1919` | `+0.78%` |
| `ALGO-USDT` | `0.0952` | `0.0967` | `0.0945` | `+0.21%` |
| `ATOM-USDT` | `1.4698` | `1.5206` | `1.461` | `-2.90%` |
| `AVAX-USDT` | `8.791` | `9.037` | `8.413` | `+4.31%` |
| `BCH-USDT` | `282.88` | `292.98` | `281.64` | `-2.44%` |
| `BTC-USDT` | `78000.9` | `78225` | `77319.9` | `+0.79%` |
| `CAKE-USDT` | `1.958` | `1.978` | `1.919` | `+0.87%` |
| `DASH-USDT` | `49.21` | `49.52` | `47.75` | `+2.82%` |
| `DGB-USDT` | `0.003212` | `0.003238` | `0.003163` | `+0.97%` |
| `DOGE-USDT` | `0.07579` | `0.07625` | `0.0751` | `+0.82%` |
| `DOT-USDT` | `0.9511` | `0.9618` | `0.944` | `-0.62%` |
| `ETC-USDT` | `7.166` | `7.1963` | `7.0814` | `+0.72%` |
| `ETH-USDT` | `2270.32` | `2277.86` | `2243.28` | `+1.11%` |
| `LINK-USDT` | `11.73` | `11.943` | `11.4657` | `+1.65%` |
| `LTC-USDT` | `55.98` | `56.4` | `54.8` | `+1.94%` |
| `QTUM-USDT` | `0.773` | `0.782` | `0.77` | `-0.25%` |
| `SHIB-USDT` | `0.000004703` | `0.000004732` | `0.000004658` | `-0.19%` |
| `SOL-USDT` | `95.38` | `96.37` | `95.18` | `-0.23%` |
| `TRX-USDT` | `0.3111` | `0.3252` | `0.3008` | `-4.33%` |
| `UNI-USDT` | `7.2507` | `7.2995` | `6.9223` | `+4.29%` |
| `XLM-USDT` | `0.169` | `0.1719` | `0.1677` | `+0.17%` |
| `XMR-USDT` | `605.08` | `610.44` | `590.61` | `+1.61%` |
| `XRP-USDT` | `1.25611` | `1.25979` | `1.2457` | `+0.64%` |

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
    "lastUpdated": "2026-11-01 10:56:34 UTC"
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

