# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-11 23:00:56 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2517` | `0.2563` | `0.2452` | `+0.27%` |
| `ALGO-USDT` | `0.1267` | `0.1297` | `0.1163` | `+7.28%` |
| `ATOM-USDT` | `1.9208` | `2.0527` | `1.8919` | `-1.45%` |
| `AVAX-USDT` | `10.916` | `11.004` | `10.192` | `+5.18%` |
| `BCH-USDT` | `285.75` | `287.11` | `275.37` | `+1.92%` |
| `BTC-USDT` | `83652.9` | `84195` | `82814.5` | `+0.68%` |
| `CAKE-USDT` | `2.338` | `2.338` | `2.234` | `+3.22%` |
| `DASH-USDT` | `52.48` | `53.02` | `50.43` | `+2.52%` |
| `DGB-USDT` | `0.003588` | `0.003825` | `0.003447` | `+1.21%` |
| `DOGE-USDT` | `0.08663` | `0.08765` | `0.0849` | `+0.89%` |
| `DOT-USDT` | `1.2586` | `1.2706` | `1.2248` | `+0.42%` |
| `ETC-USDT` | `8.4901` | `8.5109` | `8.2682` | `+1.09%` |
| `ETH-USDT` | `2534.48` | `2554.45` | `2497.83` | `+0.98%` |
| `LINK-USDT` | `13.3229` | `13.4791` | `12.8388` | `+2.28%` |
| `LTC-USDT` | `64.46` | `64.86` | `63.09` | `+0.71%` |
| `QTUM-USDT` | `0.997` | `1.034` | `0.985` | `-1.48%` |
| `SHIB-USDT` | `0.000005493` | `0.000005542` | `0.000005369` | `+1.06%` |
| `SOL-USDT` | `111.13` | `112.73` | `108.98` | `+0.56%` |
| `TRX-USDT` | `0.3304` | `0.3318` | `0.33` | `-0.15%` |
| `UNI-USDT` | `7.7579` | `7.8995` | `7.4792` | `+1.93%` |
| `XLM-USDT` | `0.2028` | `0.206` | `0.1944` | `+3.04%` |
| `XMR-USDT` | `538.97` | `545.72` | `516.04` | `+3.33%` |
| `XRP-USDT` | `1.40869` | `1.4263` | `1.38742` | `+0.32%` |

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
    "lastUpdated": "2026-10-11 23:00:56 UTC"
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

