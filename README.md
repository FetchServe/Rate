# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-31 00:21:25 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1956` | `0.1957` | `0.1823` | `+5.04%` |
| `ALGO-USDT` | `0.0957` | `0.0962` | `0.0894` | `+4.59%` |
| `ATOM-USDT` | `1.551` | `1.5547` | `1.4368` | `+5.48%` |
| `AVAX-USDT` | `8.579` | `8.676` | `7.999` | `+5.00%` |
| `BCH-USDT` | `296.08` | `297.65` | `263.2` | `+9.98%` |
| `BTC-USDT` | `77346.6` | `78778.7` | `76282` | `-0.04%` |
| `CAKE-USDT` | `1.932` | `1.932` | `1.84` | `+3.09%` |
| `DASH-USDT` | `48.94` | `50.47` | `46.02` | `+4.43%` |
| `DGB-USDT` | `0.003336` | `0.003399` | `0.00305` | `+2.80%` |
| `DOGE-USDT` | `0.07621` | `0.07682` | `0.07231` | `+2.83%` |
| `DOT-USDT` | `0.9794` | `0.9811` | `0.8692` | `+9.79%` |
| `ETC-USDT` | `7.2391` | `7.2588` | `6.7844` | `+4.78%` |
| `ETH-USDT` | `2247.64` | `2262.27` | `2175` | `+1.12%` |
| `LINK-USDT` | `11.5787` | `11.5885` | `10.2729` | `+10.65%` |
| `LTC-USDT` | `55.98` | `56.48` | `52.88` | `+3.68%` |
| `QTUM-USDT` | `0.785` | `0.791` | `0.757` | `+3.28%` |
| `SHIB-USDT` | `0.000004825` | `0.000004835` | `0.000004459` | `+5.69%` |
| `SOL-USDT` | `96.44` | `98.56` | `92.07` | `+2.34%` |
| `TRX-USDT` | `0.3363` | `0.3661` | `0.3296` | `-7.45%` |
| `UNI-USDT` | `7.1648` | `7.2042` | `6.2638` | `+11.41%` |
| `XLM-USDT` | `0.1713` | `0.1724` | `0.1579` | `+6.72%` |
| `XMR-USDT` | `587.66` | `640.76` | `573.62` | `-2.80%` |
| `XRP-USDT` | `1.26048` | `1.27398` | `1.20064` | `+2.95%` |

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
    "lastUpdated": "2026-10-31 00:21:25 UTC"
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

