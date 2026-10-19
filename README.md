# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-19 05:01:04 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2205` | `0.2229` | `0.2111` | `+0.18%` |
| `ALGO-USDT` | `0.1114` | `0.1131` | `0.1059` | `-0.35%` |
| `ATOM-USDT` | `1.7077` | `1.7231` | `1.6237` | `+0.67%` |
| `AVAX-USDT` | `9.76` | `9.895` | `9.261` | `-0.18%` |
| `BCH-USDT` | `277.64` | `279.04` | `264.41` | `+0.42%` |
| `BTC-USDT` | `82674` | `82866.3` | `80690.5` | `+1.07%` |
| `CAKE-USDT` | `2.205` | `2.212` | `2.106` | `+0.31%` |
| `DASH-USDT` | `48.92` | `49.59` | `46.25` | `+0.10%` |
| `DGB-USDT` | `0.003343` | `0.00378` | `0.003268` | `-3.29%` |
| `DOGE-USDT` | `0.0795` | `0.08027` | `0.07609` | `+0.11%` |
| `DOT-USDT` | `1.1205` | `1.1381` | `1.0469` | `+1.80%` |
| `ETC-USDT` | `7.7658` | `7.7811` | `7.4339` | `+0.45%` |
| `ETH-USDT` | `2425.65` | `2437.9` | `2329.43` | `+0.43%` |
| `LINK-USDT` | `12.1332` | `12.2687` | `11.5368` | `+1.20%` |
| `LTC-USDT` | `59.51` | `60.03` | `56.7` | `+1.10%` |
| `QTUM-USDT` | `0.853` | `0.877` | `0.825` | `-2.73%` |
| `SHIB-USDT` | `0.000005013` | `0.000005034` | `0.000004801` | `+0.68%` |
| `SOL-USDT` | `105.5` | `105.97` | `100.44` | `+1.64%` |
| `TRX-USDT` | `0.3313` | `0.3337` | `0.3311` | `-0.71%` |
| `UNI-USDT` | `7.3617` | `7.422` | `6.813` | `+1.80%` |
| `XLM-USDT` | `0.1789` | `0.1799` | `0.1718` | `+0.44%` |
| `XMR-USDT` | `593.99` | `607.76` | `571.84` | `-0.33%` |
| `XRP-USDT` | `1.31132` | `1.31658` | `1.25603` | `+1.13%` |

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
    "lastUpdated": "2026-10-19 05:01:04 UTC"
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

