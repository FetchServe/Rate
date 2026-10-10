# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-10 22:48:18 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2506` | `0.2594` | `0.2407` | `+3.55%` |
| `ALGO-USDT` | `0.1181` | `0.121` | `0.113` | `+4.14%` |
| `ATOM-USDT` | `1.9521` | `2.0846` | `1.917` | `-5.20%` |
| `AVAX-USDT` | `10.376` | `10.674` | `10.293` | `+0.12%` |
| `BCH-USDT` | `280.09` | `282.21` | `276.26` | `+1.38%` |
| `BTC-USDT` | `82982.8` | `83164.1` | `82561.7` | `+0.42%` |
| `CAKE-USDT` | `2.258` | `2.263` | `2.187` | `+3.01%` |
| `DASH-USDT` | `51.19` | `51.95` | `50.98` | `-0.13%` |
| `DGB-USDT` | `0.003556` | `0.003702` | `0.003456` | `-1.22%` |
| `DOGE-USDT` | `0.08575` | `0.08671` | `0.08525` | `+0.30%` |
| `DOT-USDT` | `1.2524` | `1.2965` | `1.2263` | `+1.66%` |
| `ETC-USDT` | `8.3985` | `8.5209` | `8.2966` | `+0.33%` |
| `ETH-USDT` | `2505.22` | `2519.22` | `2486.19` | `+0.61%` |
| `LINK-USDT` | `13.0114` | `13.25` | `12.7766` | `+1.42%` |
| `LTC-USDT` | `63.99` | `64.42` | `63.4` | `+0.26%` |
| `QTUM-USDT` | `1.012` | `1.019` | `0.943` | `+6.41%` |
| `SHIB-USDT` | `0.000005434` | `0.000005522` | `0.000005431` | `-0.67%` |
| `SOL-USDT` | `110.28` | `110.77` | `108.96` | `+0.87%` |
| `TRX-USDT` | `0.331` | `0.3325` | `0.3306` | `-0.36%` |
| `UNI-USDT` | `7.5998` | `7.71` | `7.2707` | `+4.20%` |
| `XLM-USDT` | `0.1967` | `0.1986` | `0.1938` | `+1.13%` |
| `XMR-USDT` | `523.07` | `534.2` | `514.52` | `-1.70%` |
| `XRP-USDT` | `1.40194` | `1.41299` | `1.39355` | `+0.46%` |

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
    "lastUpdated": "2026-10-10 22:48:18 UTC"
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

