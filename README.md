# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-09 23:22:43 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2419` | `0.2427` | `0.2315` | `+3.02%` |
| `ALGO-USDT` | `0.1144` | `0.1209` | `0.1097` | `-3.45%` |
| `ATOM-USDT` | `2.0634` | `2.0847` | `1.76` | `+16.03%` |
| `AVAX-USDT` | `10.348` | `10.502` | `10.012` | `+1.86%` |
| `BCH-USDT` | `276.68` | `284.73` | `268.98` | `-2.82%` |
| `BTC-USDT` | `82659.6` | `83510` | `81628.6` | `+0.94%` |
| `CAKE-USDT` | `2.194` | `2.203` | `2.138` | `+1.10%` |
| `DASH-USDT` | `51.27` | `52.14` | `50.38` | `+0.56%` |
| `DGB-USDT` | `0.00359` | `0.00377` | `0.003369` | `-4.19%` |
| `DOGE-USDT` | `0.08532` | `0.08559` | `0.0839` | `+0.81%` |
| `DOT-USDT` | `1.2312` | `1.2396` | `1.0887` | `+11.02%` |
| `ETC-USDT` | `8.3645` | `8.389` | `8.0272` | `+3.19%` |
| `ETH-USDT` | `2489.8` | `2520` | `2471.02` | `+0.46%` |
| `LINK-USDT` | `12.8282` | `12.9713` | `12.6371` | `+0.30%` |
| `LTC-USDT` | `63.62` | `64.53` | `63.04` | `+0.22%` |
| `QTUM-USDT` | `0.951` | `0.953` | `0.921` | `+3.25%` |
| `SHIB-USDT` | `0.000005456` | `0.000005499` | `0.00000529` | `+2.42%` |
| `SOL-USDT` | `109.29` | `112.02` | `108.44` | `-1.02%` |
| `TRX-USDT` | `0.3323` | `0.3334` | `0.3317` | `-0.24%` |
| `UNI-USDT` | `7.2933` | `7.4575` | `7.0137` | `-1.11%` |
| `XLM-USDT` | `0.1943` | `0.1958` | `0.1914` | `+0.51%` |
| `XMR-USDT` | `525.78` | `549.05` | `515.88` | `-2.80%` |
| `XRP-USDT` | `1.3949` | `1.4072` | `1.374` | `+0.59%` |

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
    "lastUpdated": "2026-10-09 23:22:43 UTC"
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

