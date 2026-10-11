# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-11 19:16:54 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2529` | `0.2563` | `0.2452` | `+0.19%` |
| `ALGO-USDT` | `0.1255` | `0.1297` | `0.1163` | `+5.81%` |
| `ATOM-USDT` | `1.927` | `2.0527` | `1.9077` | `-2.05%` |
| `AVAX-USDT` | `10.862` | `11.004` | `10.192` | `+3.74%` |
| `BCH-USDT` | `285.41` | `286` | `275.37` | `+1.51%` |
| `BTC-USDT` | `83702.3` | `84195` | `82814.5` | `+0.81%` |
| `CAKE-USDT` | `2.306` | `2.307` | `2.223` | `+3.73%` |
| `DASH-USDT` | `52.03` | `53.02` | `50.43` | `+1.32%` |
| `DGB-USDT` | `0.003588` | `0.003825` | `0.003447` | `-1.42%` |
| `DOGE-USDT` | `0.08685` | `0.08765` | `0.0849` | `+0.81%` |
| `DOT-USDT` | `1.2625` | `1.2706` | `1.2248` | `+0.48%` |
| `ETC-USDT` | `8.4622` | `8.5084` | `8.2682` | `+0.65%` |
| `ETH-USDT` | `2535.74` | `2554.45` | `2497.83` | `+0.88%` |
| `LINK-USDT` | `13.3133` | `13.4791` | `12.8388` | `+1.84%` |
| `LTC-USDT` | `64.52` | `64.82` | `63.09` | `+0.59%` |
| `QTUM-USDT` | `1.004` | `1.034` | `0.985` | `-0.49%` |
| `SHIB-USDT` | `0.00000548` | `0.000005542` | `0.000005369` | `+0.12%` |
| `SOL-USDT` | `111.39` | `112.73` | `108.98` | `+0.93%` |
| `TRX-USDT` | `0.3307` | `0.3318` | `0.3301` | `-0.06%` |
| `UNI-USDT` | `7.7345` | `7.8995` | `7.4792` | `+2.96%` |
| `XLM-USDT` | `0.2029` | `0.206` | `0.1944` | `+2.94%` |
| `XMR-USDT` | `543.34` | `543.85` | `516.04` | `+2.39%` |
| `XRP-USDT` | `1.409` | `1.4263` | `1.38742` | `+0.28%` |

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
    "lastUpdated": "2026-10-11 19:16:54 UTC"
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

