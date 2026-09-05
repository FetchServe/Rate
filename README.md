# Crypto Static Rate

<div align="center">
    <a href="https://github.com/FetchServe/Rate" title="Crypto Static Rate">
        <img src="https://raw.githubusercontent.com/FetchServe/Rate/media/CryptoStat.png" alt="Crypto Static header" width="40%">
    </a>
</div>

---

:bar_chart: JSON Format : [Latest Update](https://github.com/FetchServe/Rate/raw/main/rateStatic.json 'rate static free api crypto')

:white_check_mark: Direct : `https://github.com/FetchServe/Rate/raw/main/rateStatic.json`

:zap: Source : KuCoin public API &nbsp;|&nbsp; Pairs : `24` &nbsp;|&nbsp; Updated : `2026-09-05 11:20:30 UTC`

---

| Pair | Last Price | High 24h | Low 24h | Change 24h |
|:-----|-----------:|---------:|--------:|-----------:|
| `ADA-USDT` | `0.2129` | `0.2221` | `0.2091` | `-3.75%` |
| `ALGO-USDT` | `0.0941` | `0.0947` | `0.0896` | `+1.72%` |
| `ATOM-USDT` | `1.5377` | `1.5613` | `1.4683` | `+0.24%` |
| `AVAX-USDT` | `7.49` | `7.532` | `7.269` | `-0.15%` |
| `BCH-USDT` | `251.92` | `260.62` | `244.71` | `-3.10%` |
| `BTC-USDT` | `79626.9` | `81397.6` | `78659.3` | `-1.89%` |
| `CAKE-USDT` | `2.132` | `2.155` | `1.928` | `+5.02%` |
| `DASH-USDT` | `67.27` | `73.97` | `49.28` | `+27.35%` |
| `DGB-USDT` | `0.005011` | `0.00521` | `0.004583` | `+6.18%` |
| `DOGE-USDT` | `0.086` | `0.08802` | `0.08378` | `-2.13%` |
| `DOT-USDT` | `0.9056` | `0.9164` | `0.8419` | `+2.83%` |
| `ETC-USDT` | `7.663` | `7.7956` | `7.2979` | `+0.22%` |
| `ETH-USDT` | `2453.3` | `2531.37` | `2432.19` | `-2.74%` |
| `LINK-USDT` | `11.7349` | `12.0718` | `11.46` | `-2.55%` |
| `LTC-USDT` | `52.88` | `54.34` | `49.8` | `+3.28%` |
| `QTUM-USDT` | `0.867` | `0.87` | `0.834` | `+0.46%` |
| `RVN-USDT` | `0.00306` | `0.00309` | `0.00299` | `-0.64%` |
| `SHIB-USDT` | `0.000005399` | `0.000005435` | `0.000005159` | `+0.91%` |
| `SOL-USDT` | `102.34` | `104.5` | `100.21` | `-1.72%` |
| `TRX-USDT` | `0.3328` | `0.3334` | `0.3276` | `+1.15%` |
| `UNI-USDT` | `6.251` | `6.44` | `6.0531` | `-0.07%` |
| `XLM-USDT` | `0.1833` | `0.1852` | `0.1774` | `-0.75%` |
| `XMR-USDT` | `540.01` | `550.63` | `512.85` | `-1.85%` |
| `XRP-USDT` | `1.40387` | `1.45624` | `1.3837` | `-3.15%` |

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
    "lastUpdated": "2026-09-05 11:20:30 UTC"
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

