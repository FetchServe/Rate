# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-24 11:20:00 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2194` | `0.2304` | `0.2168` | `-1.17%` |
| `ALGO-USDT` | `0.092` | `0.0946` | `0.0911` | `-0.32%` |
| `ATOM-USDT` | `1.5689` | `1.6222` | `1.5579` | `+0.30%` |
| `AVAX-USDT` | `7.475` | `7.675` | `7.397` | `+0.32%` |
| `BCH-USDT` | `268.5` | `278.12` | `264.8` | `-1.71%` |
| `BTC-USDT` | `77857.1` | `78054.6` | `76674.1` | `+1.22%` |
| `CAKE-USDT` | `1.74` | `1.771` | `1.719` | `+1.16%` |
| `DASH-USDT` | `41.44` | `43.76` | `40.58` | `+0.97%` |
| `DGB-USDT` | `0.004821` | `0.005626` | `0.004617` | `-13.47%` |
| `DOGE-USDT` | `0.0911` | `0.09452` | `0.09016` | `-1.15%` |
| `DOT-USDT` | `0.9039` | `0.9368` | `0.892` | `-0.73%` |
| `ETC-USDT` | `7.7234` | `8.0316` | `7.6475` | `-1.38%` |
| `ETH-USDT` | `2469.01` | `2488.52` | `2388.51` | `+1.99%` |
| `LINK-USDT` | `11.5857` | `11.9608` | `11.2573` | `+2.29%` |
| `LTC-USDT` | `52.89` | `54.08` | `51.29` | `+1.24%` |
| `QTUM-USDT` | `0.882` | `0.901` | `0.858` | `+2.79%` |
| `RVN-USDT` | `0.00327` | `0.00344` | `0.00323` | `+0.00%` |
| `SHIB-USDT` | `0.000005428` | `0.000005598` | `0.000005347` | `+0.68%` |
| `SOL-USDT` | `94.71` | `96.24` | `93.24` | `+0.87%` |
| `TRX-USDT` | `0.3439` | `0.3449` | `0.343` | `+0.05%` |
| `UNI-USDT` | `4.3098` | `4.7066` | `4.2494` | `+0.00%` |
| `XLM-USDT` | `0.1959` | `0.2021` | `0.1917` | `+1.08%` |
| `XMR-USDT` | `422.92` | `433.12` | `413.51` | `-2.21%` |
| `XRP-USDT` | `1.48009` | `1.55079` | `1.45325` | `-0.09%` |

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
    "lastUpdated": "2026-08-24 11:20:00 UTC"
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

