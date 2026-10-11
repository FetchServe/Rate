# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-11 01:26:40 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2485` | `0.2594` | `0.246` | `+1.01%` |
| `ALGO-USDT` | `0.1191` | `0.121` | `0.1135` | `+2.76%` |
| `ATOM-USDT` | `1.9672` | `2.0458` | `1.917` | `-1.91%` |
| `AVAX-USDT` | `10.379` | `10.674` | `10.293` | `+0.71%` |
| `BCH-USDT` | `278.91` | `282.21` | `277.34` | `+0.40%` |
| `BTC-USDT` | `83020.9` | `83164.1` | `82573.7` | `+0.46%` |
| `CAKE-USDT` | `2.268` | `2.271` | `2.187` | `+2.71%` |
| `DASH-USDT` | `51.11` | `51.95` | `50.93` | `-1.06%` |
| `DGB-USDT` | `0.003527` | `0.003702` | `0.00349` | `+0.19%` |
| `DOGE-USDT` | `0.08588` | `0.08671` | `0.08557` | `+0.10%` |
| `DOT-USDT` | `1.2568` | `1.2965` | `1.2317` | `+1.94%` |
| `ETC-USDT` | `8.3834` | `8.5209` | `8.2966` | `+0.07%` |
| `ETH-USDT` | `2507.98` | `2519.22` | `2489.78` | `+0.69%` |
| `LINK-USDT` | `13.0384` | `13.25` | `12.7766` | `+1.84%` |
| `LTC-USDT` | `63.84` | `64.42` | `63.41` | `+0.40%` |
| `QTUM-USDT` | `1.01` | `1.034` | `0.943` | `+6.20%` |
| `SHIB-USDT` | `0.000005415` | `0.000005522` | `0.000005401` | `-0.95%` |
| `SOL-USDT` | `110.08` | `110.77` | `109.4` | `+0.49%` |
| `TRX-USDT` | `0.3308` | `0.3317` | `0.3306` | `-0.03%` |
| `UNI-USDT` | `7.6256` | `7.71` | `7.3081` | `+3.75%` |
| `XLM-USDT` | `0.1963` | `0.1986` | `0.1945` | `+0.87%` |
| `XMR-USDT` | `518.73` | `531.54` | `514.52` | `-0.08%` |
| `XRP-USDT` | `1.40033` | `1.41299` | `1.39674` | `-0.16%` |

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
    "lastUpdated": "2026-10-11 01:26:40 UTC"
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

