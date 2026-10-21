# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-10-21 20:49:03 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2284` | `0.2305` | `0.222` | `+2.28%` |
| `ALGO-USDT` | `0.1152` | `0.1166` | `0.1118` | `+0.96%` |
| `ATOM-USDT` | `1.7683` | `1.7884` | `1.7255` | `+0.55%` |
| `AVAX-USDT` | `9.857` | `10.048` | `9.58` | `+1.35%` |
| `BCH-USDT` | `287.69` | `290.71` | `281.23` | `+1.65%` |
| `BTC-USDT` | `84694.1` | `84897.1` | `82650.3` | `+2.30%` |
| `CAKE-USDT` | `2.251` | `2.269` | `2.218` | `+1.44%` |
| `DASH-USDT` | `52.36` | `53.96` | `49.84` | `+4.19%` |
| `DGB-USDT` | `0.003436` | `0.003443` | `0.00331` | `+1.65%` |
| `DOGE-USDT` | `0.08298` | `0.0838` | `0.08123` | `+1.28%` |
| `DOT-USDT` | `1.1718` | `1.1926` | `1.1422` | `+0.62%` |
| `ETC-USDT` | `8.1402` | `8.2021` | `7.9162` | `+2.82%` |
| `ETH-USDT` | `2493.06` | `2525.91` | `2437` | `+1.94%` |
| `LINK-USDT` | `12.6973` | `12.8068` | `12.2669` | `+3.29%` |
| `LTC-USDT` | `62.05` | `62.38` | `60.77` | `+1.42%` |
| `QTUM-USDT` | `0.9` | `0.9` | `0.872` | `+2.97%` |
| `SHIB-USDT` | `0.000005207` | `0.000005269` | `0.000005098` | `+1.61%` |
| `SOL-USDT` | `108.17` | `109.18` | `105.64` | `+1.49%` |
| `TRX-USDT` | `0.3313` | `0.3335` | `0.3304` | `+0.12%` |
| `UNI-USDT` | `7.5965` | `7.7871` | `7.3724` | `+2.60%` |
| `XLM-USDT` | `0.1855` | `0.1871` | `0.1811` | `+2.31%` |
| `XMR-USDT` | `618.15` | `624` | `570.32` | `-0.34%` |
| `XRP-USDT` | `1.38719` | `1.39891` | `1.33092` | `+3.99%` |

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
    "lastUpdated": "2026-10-21 20:49:03 UTC"
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

