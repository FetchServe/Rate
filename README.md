# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-31 09:10:26 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1969` | `0.2061` | `0.1896` | `-1.89%` |
| `ALGO-USDT` | `0.0856` | `0.0889` | `0.0832` | `-1.49%` |
| `ATOM-USDT` | `1.4799` | `1.5397` | `1.4369` | `+0.09%` |
| `AVAX-USDT` | `7.225` | `7.469` | `7.017` | `-1.43%` |
| `BCH-USDT` | `249.09` | `255.32` | `239.47` | `+1.46%` |
| `BTC-USDT` | `78692.5` | `79393.5` | `77019.1` | `+0.78%` |
| `CAKE-USDT` | `1.866` | `1.918` | `1.744` | `+6.44%` |
| `DASH-USDT` | `42.09` | `44.52` | `40.55` | `+3.01%` |
| `DGB-USDT` | `0.004784` | `0.004905` | `0.004693` | `-1.70%` |
| `DOGE-USDT` | `0.08308` | `0.08646` | `0.0808` | `-1.84%` |
| `DOT-USDT` | `0.8316` | `0.8709` | `0.8069` | `-1.21%` |
| `ETC-USDT` | `7.2451` | `7.5231` | `7.0803` | `-2.12%` |
| `ETH-USDT` | `2449.14` | `2534.24` | `2387.75` | `-0.30%` |
| `LINK-USDT` | `11.3021` | `11.7982` | `10.9932` | `-0.69%` |
| `LTC-USDT` | `48.85` | `50.13` | `47.42` | `-0.50%` |
| `QTUM-USDT` | `0.825` | `0.825` | `0.782` | `+2.10%` |
| `RVN-USDT` | `0.00299` | `0.00311` | `0.00285` | `-0.66%` |
| `SHIB-USDT` | `0.000005067` | `0.000005232` | `0.000004885` | `-0.60%` |
| `SOL-USDT` | `103.25` | `107.45` | `100.34` | `-1.50%` |
| `TRX-USDT` | `0.3367` | `0.3416` | `0.3354` | `-1.11%` |
| `UNI-USDT` | `5.1772` | `5.4884` | `4.7896` | `+7.21%` |
| `XLM-USDT` | `0.1771` | `0.1824` | `0.1717` | `-1.17%` |
| `XMR-USDT` | `522.59` | `527.51` | `474.82` | `+9.43%` |
| `XRP-USDT` | `1.3753` | `1.43323` | `1.33499` | `-1.14%` |

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
    "lastUpdated": "2026-08-31 09:10:26 UTC"
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

