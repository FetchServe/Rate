# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-21 23:51:15 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2252` | `0.2305` | `0.222` | `+0.53%` |
| `ALGO-USDT` | `0.1132` | `0.1166` | `0.1118` | `-0.43%` |
| `ATOM-USDT` | `1.754` | `1.7884` | `1.7255` | `+0.29%` |
| `AVAX-USDT` | `9.658` | `10.048` | `9.58` | `-0.95%` |
| `BCH-USDT` | `285.81` | `290.71` | `283.06` | `+0.89%` |
| `BTC-USDT` | `84167.8` | `84897.1` | `82650.3` | `+1.40%` |
| `CAKE-USDT` | `2.238` | `2.269` | `2.224` | `+0.58%` |
| `DASH-USDT` | `51.62` | `53.96` | `49.84` | `+2.25%` |
| `DGB-USDT` | `0.003397` | `0.003443` | `0.003336` | `+1.82%` |
| `DOGE-USDT` | `0.08186` | `0.0838` | `0.08123` | `-0.04%` |
| `DOT-USDT` | `1.1436` | `1.1926` | `1.1422` | `-0.60%` |
| `ETC-USDT` | `8.0721` | `8.2021` | `7.9199` | `+1.68%` |
| `ETH-USDT` | `2471.43` | `2525.91` | `2437` | `+0.89%` |
| `LINK-USDT` | `12.4903` | `12.8068` | `12.2669` | `+1.26%` |
| `LTC-USDT` | `61.45` | `62.38` | `61` | `-0.21%` |
| `QTUM-USDT` | `0.891` | `0.9` | `0.872` | `+1.94%` |
| `SHIB-USDT` | `0.000005153` | `0.000005269` | `0.000005098` | `+0.25%` |
| `SOL-USDT` | `106.8` | `109.18` | `105.64` | `+0.23%` |
| `TRX-USDT` | `0.3309` | `0.3335` | `0.3304` | `-0.15%` |
| `UNI-USDT` | `7.4324` | `7.7871` | `7.3724` | `-0.16%` |
| `XLM-USDT` | `0.1834` | `0.1871` | `0.1811` | `+0.71%` |
| `XMR-USDT` | `623.49` | `630.9` | `570.32` | `+3.66%` |
| `XRP-USDT` | `1.36359` | `1.39891` | `1.33154` | `+2.03%` |

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
    "lastUpdated": "2026-10-21 23:51:15 UTC"
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

