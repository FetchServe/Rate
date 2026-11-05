# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-05 01:34:31 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1967` | `0.2016` | `0.1828` | `+5.46%` |
| `ALGO-USDT` | `0.1` | `0.1009` | `0.0899` | `+8.93%` |
| `ATOM-USDT` | `1.4834` | `1.4914` | `1.3775` | `+6.13%` |
| `AVAX-USDT` | `8.694` | `9.159` | `8.283` | `+4.03%` |
| `BCH-USDT` | `282.51` | `285.74` | `265.4` | `+4.37%` |
| `BTC-USDT` | `80567.7` | `81199.2` | `75739.5` | `+4.77%` |
| `CAKE-USDT` | `2` | `2.044` | `1.821` | `+8.16%` |
| `DASH-USDT` | `49.16` | `49.96` | `44.07` | `+8.97%` |
| `DGB-USDT` | `0.00318` | `0.00325` | `0.003055` | `+3.11%` |
| `DOGE-USDT` | `0.077` | `0.07837` | `0.0723` | `+4.19%` |
| `DOT-USDT` | `0.9565` | `0.9954` | `0.907` | `+3.30%` |
| `ETC-USDT` | `7.3154` | `7.4057` | `6.8237` | `+5.12%` |
| `ETH-USDT` | `2423.44` | `2449.7` | `2226.62` | `+7.24%` |
| `LINK-USDT` | `11.4203` | `11.7965` | `10.6324` | `+5.28%` |
| `LTC-USDT` | `56.19` | `57.04` | `52.11` | `+5.56%` |
| `QTUM-USDT` | `0.757` | `0.77` | `0.727` | `+1.88%` |
| `SHIB-USDT` | `0.00000473` | `0.000004853` | `0.000004479` | `+4.11%` |
| `SOL-USDT` | `95.85` | `98.15` | `89.91` | `+4.38%` |
| `TRX-USDT` | `0.3198` | `0.3232` | `0.3188` | `-0.86%` |
| `UNI-USDT` | `7.6801` | `7.8185` | `6.9428` | `+8.35%` |
| `XLM-USDT` | `0.1677` | `0.1711` | `0.1571` | `+5.00%` |
| `XMR-USDT` | `636.14` | `648` | `623.82` | `+1.74%` |
| `XRP-USDT` | `1.30255` | `1.34173` | `1.24181` | `+4.24%` |

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
    "lastUpdated": "2026-11-05 01:34:31 UTC"
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

