# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-26 05:16:54 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1493` | `0.1495` | `0.1357` | `+4.55%` |
| `ALGO-USDT` | `0.0799` | `0.0804` | `0.0747` | `+2.96%` |
| `ATOM-USDT` | `1.2253` | `1.2756` | `1.2017` | `-1.40%` |
| `AVAX-USDT` | `6.702` | `6.748` | `6.244` | `+3.06%` |
| `BCH-USDT` | `208.42` | `210.02` | `190.68` | `+5.97%` |
| `BTC-USDT` | `60930.1` | `61615.2` | `57300` | `+3.05%` |
| `CAKE-USDT` | `1.576` | `1.585` | `1.457` | `+4.71%` |
| `DASH-USDT` | `36.82` | `36.88` | `32.85` | `+8.38%` |
| `DGB-USDT` | `0.002547` | `0.002634` | `0.002385` | `+2.57%` |
| `DOGE-USDT` | `0.05682` | `0.0572` | `0.05219` | `+4.00%` |
| `DOT-USDT` | `0.668` | `0.675` | `0.6194` | `+2.72%` |
| `ETC-USDT` | `5.9429` | `5.9969` | `5.5451` | `+3.12%` |
| `ETH-USDT` | `1699.9` | `1729.75` | `1608.86` | `+2.54%` |
| `LINK-USDT` | `9.2339` | `9.255` | `8.466` | `+5.26%` |
| `LTC-USDT` | `43.85` | `44.03` | `39.52` | `+8.59%` |
| `QTUM-USDT` | `0.639` | `0.644` | `0.598` | `+1.91%` |
| `SHIB-USDT` | `0.000003656` | `0.000003669` | `0.000003392` | `+3.80%` |
| `SOL-USDT` | `71.19` | `71.9` | `65.85` | `+3.73%` |
| `TRX-USDT` | `0.3038` | `0.3092` | `0.3026` | `-1.61%` |
| `UNI-USDT` | `4.7537` | `4.8541` | `4.3655` | `+3.27%` |
| `XLM-USDT` | `0.1288` | `0.1307` | `0.1198` | `+4.37%` |
| `XMR-USDT` | `520.03` | `526.48` | `497` | `+1.13%` |
| `XRP-USDT` | `0.96086` | `0.9616` | `0.88902` | `+4.74%` |

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
    "lastUpdated": "2026-11-26 05:16:54 UTC"
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

