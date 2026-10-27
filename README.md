# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-27 22:47:30 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2051` | `0.2072` | `0.2013` | `-0.09%` |
| `ALGO-USDT` | `0.1033` | `0.1062` | `0.1018` | `-0.86%` |
| `ATOM-USDT` | `1.6178` | `1.6422` | `1.6048` | `-1.17%` |
| `AVAX-USDT` | `8.928` | `8.987` | `8.667` | `+0.31%` |
| `BCH-USDT` | `291.82` | `295.1` | `277.23` | `+4.49%` |
| `BTC-USDT` | `80879` | `81286.9` | `79509.3` | `+1.12%` |
| `CAKE-USDT` | `2.076` | `2.164` | `2.042` | `-2.44%` |
| `DASH-USDT` | `55.21` | `55.86` | `52.72` | `+4.30%` |
| `DGB-USDT` | `0.003337` | `0.00345` | `0.003216` | `-0.86%` |
| `DOGE-USDT` | `0.07868` | `0.07898` | `0.07668` | `+1.75%` |
| `DOT-USDT` | `0.998` | `1.0146` | `0.9775` | `-0.68%` |
| `ETC-USDT` | `7.6085` | `7.6451` | `7.471` | `+0.49%` |
| `ETH-USDT` | `2349.52` | `2364.16` | `2297.79` | `+1.60%` |
| `LINK-USDT` | `11.5298` | `11.5974` | `11.2288` | `+1.82%` |
| `LTC-USDT` | `56.92` | `57.17` | `55.74` | `+0.81%` |
| `QTUM-USDT` | `0.832` | `0.832` | `0.808` | `+0.84%` |
| `SHIB-USDT` | `0.000004884` | `0.000004912` | `0.000004798` | `+0.61%` |
| `SOL-USDT` | `101.27` | `101.88` | `99.17` | `+0.91%` |
| `TRX-USDT` | `0.3314` | `0.3321` | `0.3273` | `+0.45%` |
| `UNI-USDT` | `7.0738` | `7.2101` | `6.9453` | `-0.01%` |
| `XLM-USDT` | `0.17` | `0.1714` | `0.1665` | `+1.19%` |
| `XMR-USDT` | `607.58` | `613.23` | `585.65` | `+1.59%` |
| `XRP-USDT` | `1.32448` | `1.33042` | `1.28532` | `+2.51%` |

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
    "lastUpdated": "2026-10-27 22:47:30 UTC"
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

