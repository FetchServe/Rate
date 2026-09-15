# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-15 23:00:09 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1953` | `0.21` | `0.193` | `-6.91%` |
| `ALGO-USDT` | `0.0891` | `0.0984` | `0.088` | `-7.47%` |
| `ATOM-USDT` | `1.5122` | `1.6101` | `1.5` | `-4.40%` |
| `AVAX-USDT` | `7.279` | `7.63` | `7.191` | `-4.48%` |
| `BCH-USDT` | `216.95` | `225.48` | `212.98` | `-3.78%` |
| `BTC-USDT` | `75666.7` | `78563.5` | `74973.8` | `-3.68%` |
| `CAKE-USDT` | `2.212` | `2.358` | `2.193` | `-6.19%` |
| `DASH-USDT` | `50.6` | `54.13` | `49.6` | `-5.96%` |
| `DGB-USDT` | `0.003638` | `0.004503` | `0.003583` | `-17.01%` |
| `DOGE-USDT` | `0.08019` | `0.08415` | `0.07846` | `-4.62%` |
| `DOT-USDT` | `0.9456` | `1.0124` | `0.9339` | `-6.30%` |
| `ETC-USDT` | `7.2168` | `7.6129` | `7.0913` | `-5.15%` |
| `ETH-USDT` | `2396.83` | `2534.49` | `2358.8` | `-5.38%` |
| `LINK-USDT` | `10.9043` | `11.6285` | `10.7897` | `-5.75%` |
| `LTC-USDT` | `51.24` | `53.45` | `50.77` | `-4.06%` |
| `QTUM-USDT` | `0.855` | `0.938` | `0.844` | `-8.84%` |
| `RVN-USDT` | `0.00223` | `0.00238` | `0.00221` | `-4.70%` |
| `SHIB-USDT` | `0.00000495` | `0.000005268` | `0.000004898` | `-5.94%` |
| `SOL-USDT` | `97.13` | `103.01` | `95.81` | `-5.58%` |
| `TRX-USDT` | `0.3332` | `0.3397` | `0.3317` | `-1.62%` |
| `UNI-USDT` | `6.3513` | `6.835` | `6.1667` | `-2.83%` |
| `XLM-USDT` | `0.1764` | `0.1986` | `0.1742` | `-8.88%` |
| `XMR-USDT` | `505.94` | `520` | `492.85` | `-1.71%` |
| `XRP-USDT` | `1.28903` | `1.45966` | `1.26488` | `-10.19%` |

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
    "lastUpdated": "2026-09-15 23:00:09 UTC"
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

