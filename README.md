# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-26 15:32:14 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1477` | `0.15` | `0.1377` | `+6.95%` |
| `ALGO-USDT` | `0.0791` | `0.0811` | `0.0748` | `+5.18%` |
| `ATOM-USDT` | `1.1789` | `1.2756` | `1.1755` | `-2.46%` |
| `AVAX-USDT` | `6.538` | `6.748` | `6.304` | `+3.49%` |
| `BCH-USDT` | `206.05` | `210.02` | `193.45` | `+6.48%` |
| `BTC-USDT` | `60332.4` | `61615.2` | `57903` | `+3.87%` |
| `CAKE-USDT` | `1.563` | `1.588` | `1.484` | `+5.32%` |
| `DASH-USDT` | `35.46` | `36.91` | `33.45` | `+5.53%` |
| `DGB-USDT` | `0.002533` | `0.002634` | `0.002385` | `+5.14%` |
| `DOGE-USDT` | `0.05628` | `0.05727` | `0.05294` | `+5.98%` |
| `DOT-USDT` | `0.6613` | `0.6791` | `0.625` | `+5.52%` |
| `ETC-USDT` | `5.8794` | `5.9969` | `5.5959` | `+4.97%` |
| `ETH-USDT` | `1684.71` | `1729.75` | `1630.04` | `+2.94%` |
| `LINK-USDT` | `9.1257` | `9.2903` | `8.5732` | `+6.12%` |
| `LTC-USDT` | `43.24` | `44.03` | `39.94` | `+8.10%` |
| `QTUM-USDT` | `0.632` | `0.644` | `0.607` | `+3.77%` |
| `SHIB-USDT` | `0.000003616` | `0.000003669` | `0.000003408` | `+5.82%` |
| `SOL-USDT` | `70.57` | `71.9` | `66.75` | `+5.31%` |
| `TRX-USDT` | `0.3021` | `0.3051` | `0.3021` | `-0.32%` |
| `UNI-USDT` | `4.59` | `4.8541` | `4.4284` | `+3.32%` |
| `XLM-USDT` | `0.1262` | `0.1307` | `0.1211` | `+4.12%` |
| `XMR-USDT` | `443.57` | `529.3` | `435.92` | `-11.37%` |
| `XRP-USDT` | `0.94233` | `0.96379` | `0.89341` | `+5.33%` |

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
    "lastUpdated": "2026-11-26 15:32:14 UTC"
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

