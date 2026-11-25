# Awesome Hyperliquid Stocks

> Stock, index, commodity, FX and pre-IPO perpetuals on Hyperliquid, deployed through HIP-3.

A curated list of the markets, deployers, apps, data sources and guides for trading traditional assets as perps on Hyperliquid. Every entry was checked on 2026-11-19. Nothing here is investment advice.

## Contents

- [What is HIP-3](#what-is-hip-3)
- [Markets](#markets)
- [Deployers](#deployers)
- [Apps](#apps)
- [Market data and trackers](#market-data-and-trackers)
- [Guides](#guides)
- [Pre-IPO perps](#pre-ipo-perps)
- [Incidents worth reading](#incidents-worth-reading)
- [Risks](#risks)

## What is HIP-3

- HIP-3 lets a builder who stakes HYPE deploy its own perp markets on Hyperliquid's order book. The deployer runs the oracle and sets leverage and settlement rules.
- Each deployer has its own dex name, and its markets show up as `dex:TICKER`, for example `xyz:NVDA` or `io:OAI`.
- These are perpetual futures that track a price. You do not own shares, get dividends or vote.
- On 2026-11-19, four deployers had live markets: `xyz` (122), `para` (33), `io` (17) and `mkts` (1). Six other deployers had delisted all their markets. Source: Hyperliquid API, `perpDexs` and `metaAndAssetCtxs`.

## Markets

A selection of live markets on 2026-11-19. Linked market pages show price, hourly funding, open interest and 24h volume from the Hyperliquid API.

### US stocks

- [Nvidia (xyz:NVDA)](https://perpex.co/markets/hip-3/xyz/nvidia) - The most traded HIP-3 market on 2026-11-19.
- [Tesla (xyz:TSLA)](https://perpex.co/markets/hip-3/xyz/tesla) - Tesla stock perp.
- [Micron (xyz:MU)](https://perpex.co/markets/hip-3/xyz/micron) - Micron stock perp.
- Also on `xyz`: AAPL, MSFT, GOOGL, AMZN, META, AMD, AVGO, ORCL, PLTR, NFLX, INTC, ARM, TSM, COIN, HOOD, MSTR, CRCL and more.

### Indices and ETFs

- [XYZ100 (xyz:XYZ100)](https://perpex.co/markets/hip-3/xyz/xyz100) - US index perp from trade.xyz.
- Also on `xyz`: SP500, SMH, SOXL, XLE, TLT, XBI, and country markets such as EWY (Korea), EWJ (Japan), EWZ (Brazil), JP225 and NIFTY.
- On `para`: rates (2Y, 10Y, 30Y), sector baskets and crypto-dominance indices.

### Commodities

- [Gold (xyz:GOLD)](https://perpex.co/markets/hip-3/xyz/gold) - Gold perp.
- [Silver (xyz:SILVER)](https://perpex.co/markets/hip-3/xyz/silver) - Silver perp.
- [WTI crude oil (xyz:CL)](https://perpex.co/markets/hip-3/xyz/crude-oil) - WTI oil perp.
- Also on `xyz`: BRENTOIL, NATGAS, COPPER, PLATINUM and PALLADIUM.

### FX

- On `xyz`: EUR, JPY and GBP.

### Asian stocks

- On `xyz` and `io`: SK Hynix, Samsung, SoftBank, Hyundai, Alibaba, Xiaomi, Tencent and more.

### Pre-IPO companies

- [Anthropic (xyz:ANT)](https://perpex.co/markets/hip-3/xyz/anthropic) - Anthropic perp. It moves to share-price tracking at listing.
- [SpaceX (xyz:SPCX)](https://perpex.co/markets/hip-3/xyz/spacex) - SpaceX perp.
- On `io`: OpenAI (OAI) and Anthropic (ANTH), quoted in company valuation.

## Deployers

- [trade.xyz](https://app.trade.xyz) - Deployer of `xyz`, the largest HIP-3 dex: US and Asian stocks, indices, commodities, FX and pre-IPO markets.
- [Entropy](https://entropy.io/trade) - Deployer of `io`: equities, indices and pre-IPO companies such as OpenAI and Anthropic.
- [Paragon](https://www.paragon.trade) - Deployer of `para`: rates, sector and theme baskets, and crypto-dominance markets. Traded through other frontends.
- [Markets.xyz](https://markets.xyz) - Kinetiq's app and `mkts` dex, with stocks, commodities and pre-IPO markets.

## Apps

Apps that let you trade HIP-3 markets from your own wallet. Market lists and access vary by app and region.

- [Perpex](https://perpex.co) - Self-custodial Hyperliquid app with stock, index, commodity and pre-IPO markets, market pages, wallet analysis and copy trading. Web, iOS, Android.
- [Based](https://based.one) - Self-custody app with US and Asian stock perps next to crypto perps. Web, iOS, Android.
- [Coinbase Wallet](https://wallet.coinbase.com) - Coinbase's self-custody wallet with Hyperliquid perps on stocks and commodities. iOS, Android.
- [Dexari](https://dexari.com) - Mobile wallet with stock, commodity, FX and index perps on Hyperliquid. iOS, Android.
- [Dexly](https://dexly.trade) - Hyperliquid terminal with US stock, gold and index perps. Web, iOS, Android.
- [Dreamcash](https://dreamcash.xyz) - Self-custodial Hyperliquid app with HIP-3 stock and commodity markets. Web, desktop, iOS, Android.
- [Farao](https://getfarao.com) - Social copy trading app with stock, index, commodity and pre-IPO perps settled on Hyperliquid. iOS, Android.
- [fomo](https://fomo.family/perpetual-futures) - Social trading app with Hyperliquid and trade.xyz stock, index and pre-IPO perps. Not available in the US. Web, iOS, Android.
- [Hyperdash](https://hyperdash.com) - Trading platform covering Hyperliquid equity, commodity, FX and crypto markets. Web.
- [Lit](https://www.lit.trade) - Trading terminal that aggregates HIP-3 equity and commodity markets. Web.
- [MetaMask](https://metamask.com/perps) - Wallet with Hyperliquid-powered perps on US stocks, the S&P 500 and pre-IPO names. iOS, Android, extension.
- [Phantom](https://phantom.com/perpetual-futures) - Multichain wallet whose Hyperliquid-powered perps include equity markets. iOS, Android, extension.

## Market data and trackers

- [Perpex HIP-3 markets](https://perpex.co/markets/hip-3) - Every live HIP-3 dex with its markets, 24h volume and open interest.
- [Allium HIP-3](https://hyperliquid.allium.so/hip3) - HIP-3 dashboard on Allium's free Hyperliquid portal.
- [AlphaYou Hyperliquid stocks](https://alphayou.net/hyperliquid/stocks) - Stock perps with the long and short positions tracked traders hold in each.
- [ASXN HIP-3 dashboard](https://data.asxn.xyz/dashboard/hip-3) - ASXN's dashboard for HIP-3 markets.
- [Coinperps HIP-3 statistics](https://www.coinperps.com/learn/hyperliquid-hip-3-statistics) - Volume, open interest, deployer share and incident history.
- [Hyperliquid API](https://hyperliquid.gitbook.io/hyperliquid-docs/for-developers/api) - Official info endpoint; `perpDexs` lists every HIP-3 dex and its markets.
- [HypurrScan HIP-3](https://hypurrscan.io/hip3) - Explorer page of HIP-3 dexs and their markets.
- [The Block Data](https://www.theblock.co/data/hyperliquid) - Charts including daily HIP-3 open interest by dex.

## Guides

- [HIP-3 specification](https://hyperliquid.gitbook.io/hyperliquid-docs/hyperliquid-improvement-proposals-hips/hip-3-builder-deployed-perpetuals) - Deployer duties, staking requirement, oracles and fee split.
- [trade.xyz: Oracle price](https://docs.trade.xyz/perpetuals/mechanics/oracle-price) - How prices are set during market hours and from the order book when markets are closed.
- [trade.xyz: US stock sessions](https://docs.trade.xyz/perpetuals/markets/stocks/us) - Pre-market, regular, post-market and overnight sessions.
- [trade.xyz: Weekend and holiday pricing](https://docs.trade.xyz/perpetuals/specifications-and-schedules/holiday-closures) - When markets switch to internal pricing.
- [trade.xyz: Discovery bounds](https://docs.trade.xyz/perpetuals/mechanics/discovery-bounds) - Price limits while external prices are unavailable.
- [trade.xyz: Specification index](https://docs.trade.xyz/perpetuals/specifications-and-schedules/specification-index) - Maximum leverage, margin mode and sessions for each market.
- [trade.xyz: Fees](https://docs.trade.xyz/perpetuals/mechanics/fees) - How HIP-3 fees are set and shared with Hyperliquid.
- [trade.xyz: Commodities](https://docs.trade.xyz/perpetuals/markets/commodities) - How commodity perps are priced.
- [Paragon: Equities off-hours](https://docs.paragon.trade/markets/equities/off-hours-and-fallback) - Paragon's equity pricing when markets are closed.
- [Entropy: Equity oracle price](https://docs.entropy.io/equity-perp-mechanics/oracle-price) - Entropy's equity pricing in and outside regular sessions.

## Pre-IPO perps

- [Perpex: Anthropic IPO pre-market report](https://perpex.co/research/anthropic-ipo-hyperliquid-pre-market) - Wallet-level data on Anthropic's pre-IPO perps before the listing, compared with SpaceX.
- [trade.xyz: Pre-IPO perpetuals](https://docs.trade.xyz/perpetuals/markets/pre-ipo-perpetuals) - What pre-IPO perps are and how they convert at listing.
- [trade.xyz: Alternative settlement events](https://docs.trade.xyz/perpetuals/markets/pre-ipo-perpetuals/alternative-settlement-events) - What happens if the IPO does not happen, or on a merger.
- [Entropy: Pre-IPO perpetuals](https://docs.entropy.io/market-types/pre-ipo-perpetuals) - Valuation-quoted markets and how they convert to share price after listing.
- [Entropy: No-IPO resolution](https://docs.entropy.io/pre-ipo-perp-mechanics/no-ipo-resolution) - Scheduled end and settlement if a company does not list.

## Incidents worth reading

- [Galaxy Research: trade.xyz oracle and liquidations](https://www.galaxy.com/insights/research/hyperliquid-tradexyz-oracle-liquidations) - Analysis of the July 2026 SK Hynix oracle event and HIP-3 oracle design.
- [hip3-oracle-guard: SK Hynix oracle postmortem](https://github.com/imokokok/hip3-oracle-guard/blob/main/docs/postmortem/2026-07-28-sk-hynix.md) - Technical teardown of the July 2026 trade.xyz SK Hynix oracle event and its liquidations.
- [Nexus Mutual: SK Hynix flash crash report](https://nexusmutual.io/blog/xyz-skhynix-flash-crash-on-hyperliquid-incident-report) - Timeline of the same event and its liquidations.
- [The Block: Ventuals SpaceX perp plunge](https://www.theblock.co/post/402991/ventuals-to-compensate-traders-after-pre-ipo-spacex-perps-plunge-45-on-hyperliquid) - A pre-IPO perp that fell on bad oracle data in May 2026.

## Risks

- Outside market hours, many HIP-3 markets price from their own order book. Prices can move away from the underlying, and positions can be liquidated over weekends.
- Each market depends on its deployer's oracle. Oracle errors have caused large liquidations.
- Deployers can stop. Six HIP-3 deployers delisted all their markets in 2026.
- Pre-IPO perps are cash-settled bets on a valuation. Read the settlement rules for listing, no listing and mergers.
- Leverage limits, fees and availability differ by market, app and country.

## Contributing

Additions and fixes are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first: one entry per pull request, a live product that states HIP-3 or Hyperliquid stock-perp support on its own site, and a neutral description.

If this list helped you, a star helps others find it.
