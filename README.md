# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-12 02:32:08 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2502` | `0.2563` | `0.2452` | `+0.36%` |
| `ALGO-USDT` | `0.1275` | `0.1297` | `0.1163` | `+7.32%` |
| `ATOM-USDT` | `1.9127` | `2.0527` | `1.8919` | `-2.99%` |
| `AVAX-USDT` | `10.908` | `11.03` | `10.192` | `+5.51%` |
| `BCH-USDT` | `286.79` | `288.41` | `275.37` | `+3.04%` |
| `BTC-USDT` | `83927.8` | `84195` | `82814.5` | `+1.04%` |
| `CAKE-USDT` | `2.373` | `2.373` | `2.234` | `+5.00%` |
| `DASH-USDT` | `52.48` | `53.33` | `50.43` | `+2.70%` |
| `DGB-USDT` | `0.003536` | `0.003825` | `0.003447` | `+1.20%` |
| `DOGE-USDT` | `0.08695` | `0.08765` | `0.0849` | `+1.21%` |
| `DOT-USDT` | `1.2433` | `1.2706` | `1.2248` | `-0.65%` |
| `ETC-USDT` | `8.4391` | `8.5109` | `8.2682` | `+0.42%` |
| `ETH-USDT` | `2555.07` | `2563.92` | `2497.83` | `+1.75%` |
| `LINK-USDT` | `13.3828` | `13.4791` | `12.8388` | `+2.87%` |
| `LTC-USDT` | `65.02` | `65.47` | `63.09` | `+2.00%` |
| `QTUM-USDT` | `0.986` | `1.034` | `0.981` | `-3.89%` |
| `SHIB-USDT` | `0.000005477` | `0.000005542` | `0.000005369` | `+0.97%` |
| `SOL-USDT` | `112.12` | `112.73` | `108.98` | `+1.81%` |
| `TRX-USDT` | `0.3308` | `0.3318` | `0.33` | `+0.09%` |
| `UNI-USDT` | `7.7008` | `7.8995` | `7.4792` | `+0.45%` |
| `XLM-USDT` | `0.202` | `0.206` | `0.1944` | `+2.90%` |
| `XMR-USDT` | `534.78` | `545.72` | `522.88` | `+2.01%` |
| `XRP-USDT` | `1.40964` | `1.4263` | `1.38742` | `+0.56%` |

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
    "lastUpdated": "2026-10-12 02:32:08 UTC"
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

