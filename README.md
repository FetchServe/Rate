# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-04 21:08:03 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1969` | `0.2016` | `0.1828` | `+3.41%` |
| `ALGO-USDT` | `0.0994` | `0.1009` | `0.0899` | `+6.08%` |
| `ATOM-USDT` | `1.4558` | `1.4914` | `1.3775` | `+2.73%` |
| `AVAX-USDT` | `8.771` | `9.159` | `8.283` | `+2.72%` |
| `BCH-USDT` | `281.4` | `285.74` | `265.4` | `+2.13%` |
| `BTC-USDT` | `80279.8` | `81199.2` | `75739.5` | `+3.02%` |
| `CAKE-USDT` | `2.016` | `2.044` | `1.821` | `+7.23%` |
| `DASH-USDT` | `48.45` | `49.3` | `44.07` | `+5.07%` |
| `DGB-USDT` | `0.003072` | `0.003207` | `0.003051` | `-0.58%` |
| `DOGE-USDT` | `0.07682` | `0.07837` | `0.0723` | `+1.89%` |
| `DOT-USDT` | `0.9589` | `0.9954` | `0.907` | `+1.49%` |
| `ETC-USDT` | `7.3284` | `7.3642` | `6.8237` | `+3.73%` |
| `ETH-USDT` | `2425.46` | `2449.7` | `2226.62` | `+5.84%` |
| `LINK-USDT` | `11.4527` | `11.7965` | `10.6324` | `+3.03%` |
| `LTC-USDT` | `56.01` | `57.04` | `52.11` | `+2.67%` |
| `QTUM-USDT` | `0.751` | `0.77` | `0.727` | `+0.40%` |
| `SHIB-USDT` | `0.000004731` | `0.000004853` | `0.000004479` | `+2.18%` |
| `SOL-USDT` | `94.9` | `98.15` | `89.91` | `+1.34%` |
| `TRX-USDT` | `0.3199` | `0.3238` | `0.3188` | `-1.11%` |
| `UNI-USDT` | `7.6087` | `7.7843` | `6.9428` | `+5.25%` |
| `XLM-USDT` | `0.1662` | `0.1711` | `0.1571` | `+1.65%` |
| `XMR-USDT` | `632.94` | `648` | `623.81` | `-0.07%` |
| `XRP-USDT` | `1.30316` | `1.34173` | `1.24181` | `+1.69%` |

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
    "lastUpdated": "2026-11-04 21:08:03 UTC"
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

