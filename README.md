# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-14 16:05:35 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2089` | `0.2126` | `0.2024` | `+1.30%` |
| `ALGO-USDT` | `0.0953` | `0.101` | `0.0933` | `+2.14%` |
| `ATOM-USDT` | `1.5389` | `1.6187` | `1.5292` | `-3.80%` |
| `AVAX-USDT` | `7.46` | `7.542` | `7.262` | `+1.17%` |
| `BCH-USDT` | `223.26` | `226.03` | `219.71` | `-0.45%` |
| `BTC-USDT` | `78472.7` | `78698` | `76372.8` | `+1.70%` |
| `CAKE-USDT` | `2.362` | `2.394` | `2.194` | `+7.65%` |
| `DASH-USDT` | `53.92` | `55.2` | `52.62` | `+0.61%` |
| `DGB-USDT` | `0.0044` | `0.004585` | `0.004348` | `-2.22%` |
| `DOGE-USDT` | `0.08396` | `0.08483` | `0.08193` | `+0.41%` |
| `DOT-USDT` | `1.009` | `1.0288` | `0.9978` | `-0.75%` |
| `ETC-USDT` | `7.5941` | `7.6967` | `7.3924` | `-0.30%` |
| `ETH-USDT` | `2504.78` | `2534.63` | `2465.43` | `+0.43%` |
| `LINK-USDT` | `11.4455` | `11.5029` | `11.126` | `+1.44%` |
| `LTC-USDT` | `53.62` | `55.26` | `53.36` | `-1.54%` |
| `QTUM-USDT` | `0.936` | `0.972` | `0.93` | `-1.36%` |
| `RVN-USDT` | `0.00238` | `0.00256` | `0.00234` | `+1.27%` |
| `SHIB-USDT` | `0.000005247` | `0.000005283` | `0.000005108` | `+0.71%` |
| `SOL-USDT` | `101.94` | `102.32` | `99.02` | `+1.49%` |
| `TRX-USDT` | `0.34` | `0.3417` | `0.3328` | `-0.35%` |
| `UNI-USDT` | `6.3498` | `6.4651` | `6.0942` | `+1.53%` |
| `XLM-USDT` | `0.1939` | `0.1945` | `0.176` | `+8.68%` |
| `XMR-USDT` | `513.04` | `538.87` | `502.68` | `-4.50%` |
| `XRP-USDT` | `1.40256` | `1.40977` | `1.33424` | `+4.27%` |

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
    "lastUpdated": "2026-09-14 16:05:35 UTC"
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

