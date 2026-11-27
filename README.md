# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-27 08:53:10 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.153` | `0.1538` | `0.1459` | `+2.96%` |
| `ALGO-USDT` | `0.0824` | `0.0838` | `0.078` | `+2.74%` |
| `ATOM-USDT` | `1.2439` | `1.2519` | `1.1755` | `-0.28%` |
| `AVAX-USDT` | `6.768` | `6.805` | `6.47` | `+1.31%` |
| `BCH-USDT` | `212.57` | `219.81` | `204.32` | `+2.27%` |
| `BTC-USDT` | `61758.3` | `62228.6` | `59917.4` | `+1.38%` |
| `CAKE-USDT` | `1.598` | `1.61` | `1.551` | `+1.26%` |
| `DASH-USDT` | `36.95` | `37.23` | `34.94` | `+1.65%` |
| `DGB-USDT` | `0.002541` | `0.002591` | `0.002494` | `+1.07%` |
| `DOGE-USDT` | `0.05818` | `0.05859` | `0.05582` | `+2.48%` |
| `DOT-USDT` | `0.6868` | `0.6947` | `0.6562` | `+2.12%` |
| `ETC-USDT` | `6` | `6.0338` | `5.8332` | `+1.46%` |
| `ETH-USDT` | `1731.58` | `1755` | `1668.07` | `+1.95%` |
| `LINK-USDT` | `9.6272` | `9.7221` | `9.0403` | `+4.07%` |
| `LTC-USDT` | `44.57` | `44.87` | `42.87` | `+2.17%` |
| `QTUM-USDT` | `0.648` | `0.649` | `0.632` | `+2.04%` |
| `SHIB-USDT` | `0.000003707` | `0.000003742` | `0.000003595` | `+1.98%` |
| `SOL-USDT` | `73.34` | `73.68` | `69.79` | `+3.06%` |
| `TRX-USDT` | `0.3055` | `0.306` | `0.3018` | `+0.22%` |
| `UNI-USDT` | `4.8905` | `4.9307` | `4.5402` | `+3.00%` |
| `XLM-USDT` | `0.1297` | `0.1307` | `0.1254` | `+0.62%` |
| `XMR-USDT` | `454.88` | `527.88` | `428.1` | `-12.60%` |
| `XRP-USDT` | `0.97934` | `0.9872` | `0.93384` | `+2.37%` |

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
    "lastUpdated": "2026-11-27 08:53:10 UTC"
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

