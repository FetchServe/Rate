# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `23` &nbsp;|&nbsp; Updated : `2026-11-11 16:48:08 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.1785` | `0.1808` | `0.1713` | `+3.47%` |
| `ALGO-USDT` | `0.0914` | `0.0919` | `0.0882` | `+3.16%` |
| `ATOM-USDT` | `1.4298` | `1.4375` | `1.3643` | `+4.14%` |
| `AVAX-USDT` | `8.607` | `8.73` | `8.147` | `+5.04%` |
| `BCH-USDT` | `232.9` | `233.41` | `226.87` | `+1.64%` |
| `BTC-USDT` | `74233.8` | `74460` | `72761.8` | `+1.76%` |
| `CAKE-USDT` | `1.846` | `1.86` | `1.769` | `+2.49%` |
| `DASH-USDT` | `44.02` | `48.44` | `42.39` | `+0.73%` |
| `DGB-USDT` | `0.003044` | `0.003104` | `0.002928` | `+1.90%` |
| `DOGE-USDT` | `0.06882` | `0.06953` | `0.06661` | `+2.34%` |
| `DOT-USDT` | `0.8607` | `0.8723` | `0.8252` | `+3.00%` |
| `ETC-USDT` | `6.7451` | `6.818` | `6.6425` | `+0.96%` |
| `ETH-USDT` | `2076.39` | `2090.52` | `2012.34` | `+2.87%` |
| `LINK-USDT` | `10.4747` | `10.5491` | `10.1334` | `+2.90%` |
| `LTC-USDT` | `51.16` | `51.72` | `49.61` | `+2.52%` |
| `QTUM-USDT` | `0.697` | `0.697` | `0.682` | `+2.04%` |
| `SHIB-USDT` | `0.000004466` | `0.000004509` | `0.000004328` | `+2.80%` |
| `SOL-USDT` | `84.71` | `85.42` | `81.73` | `+3.43%` |
| `TRX-USDT` | `0.3164` | `0.3187` | `0.316` | `-0.69%` |
| `UNI-USDT` | `6.5453` | `6.8237` | `6.3402` | `-2.21%` |
| `XLM-USDT` | `0.1512` | `0.1527` | `0.1413` | `+6.40%` |
| `XMR-USDT` | `591.1` | `591.87` | `547.48` | `+5.92%` |
| `XRP-USDT` | `1.06906` | `1.07934` | `1.03951` | `+2.59%` |

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
    "lastUpdated": "2026-11-11 16:48:08 UTC"
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

