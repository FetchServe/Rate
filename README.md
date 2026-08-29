# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-08-29 16:00:49 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2007` | `0.2052` | `0.199` | `-1.85%` |
| `ALGO-USDT` | `0.0872` | `0.0877` | `0.0855` | `-0.57%` |
| `ATOM-USDT` | `1.5083` | `1.5166` | `1.4532` | `+1.96%` |
| `AVAX-USDT` | `7.335` | `7.369` | `7.206` | `+0.05%` |
| `BCH-USDT` | `244.87` | `250.06` | `242.52` | `-1.87%` |
| `BTC-USDT` | `77863.5` | `78388` | `76880.9` | `-0.59%` |
| `CAKE-USDT` | `1.726` | `1.73` | `1.675` | `+1.17%` |
| `DASH-USDT` | `42.01` | `42.44` | `36.91` | `+10.26%` |
| `DGB-USDT` | `0.004861` | `0.004989` | `0.004581` | `+3.60%` |
| `DOGE-USDT` | `0.08519` | `0.08602` | `0.08383` | `-0.90%` |
| `DOT-USDT` | `0.8405` | `0.8581` | `0.8316` | `-1.84%` |
| `ETC-USDT` | `7.5378` | `7.5758` | `7.3619` | `-0.23%` |
| `ETH-USDT` | `2444.91` | `2474.01` | `2406.54` | `-1.07%` |
| `LINK-USDT` | `11.3881` | `11.5841` | `11.2669` | `-1.56%` |
| `LTC-USDT` | `49.09` | `49.58` | `47.96` | `+1.07%` |
| `QTUM-USDT` | `0.828` | `0.852` | `0.807` | `+0.24%` |
| `RVN-USDT` | `0.00301` | `0.0031` | `0.00301` | `-2.27%` |
| `SHIB-USDT` | `0.000005147` | `0.000005222` | `0.000005054` | `-1.39%` |
| `SOL-USDT` | `105.06` | `105.71` | `102.29` | `-0.32%` |
| `TRX-USDT` | `0.3382` | `0.3422` | `0.3376` | `-0.50%` |
| `UNI-USDT` | `4.4871` | `4.5171` | `4.3488` | `+0.00%` |
| `XLM-USDT` | `0.1789` | `0.1822` | `0.1755` | `-0.61%` |
| `XMR-USDT` | `466.13` | `473.24` | `458.02` | `-0.70%` |
| `XRP-USDT` | `1.39405` | `1.41239` | `1.36386` | `-0.65%` |

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
    "lastUpdated": "2026-08-29 16:00:49 UTC"
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

