# TradeSync

> Discretionary trading journal for traders who plan trades before entering, review execution after, and iterate on their edge. TradeSync turns raw trade logs into PnL, R-multiple, win rate, and emotional patterns so you trade with data, not feelings. Multi-account isolation, 5 languages, EU region by default, GDPR-compliant.

```
+--------------------------------------------------------------+
|  T R A D E S Y N C                                           |
|  plan the trade. trade the plan. journal the outcome.        |
+--------------------------------------------------------------+
```

[![Status](https://img.shields.io/badge/status-beta-blue)](https://tradesynchub.app/)
[![Region](https://img.shields.io/badge/region-EU--Frankfurt-green)](https://tradesynchub.app/privacy)
[![GDPR](https://img.shields.io/badge/GDPR--compliant-green)](https://tradesynchub.app/privacy)
[![Languages](https://img.shields.io/badge/i18n-5%20languages-yellow)](https://tradesynchub.app/)
[![License](https://img.shields.io/badge/license-CC--BY--4.0-lightgrey)](LICENSE)
[![Open the app](https://img.shields.io/badge/%E2%96%BA_tradesynchub.app-111827?style=for-the-badge)](https://tradesynchub.app/)

---

## Snapshot

```
tradesync  v0.4.0-beta  uptime 99.97%  region eu-frankfurt
------------------------------------------------------------------------
last 30 days
  net pnl          +12,847.20 USD
  win rate              58.3%      (  35 of 60 trades )
  profit factor          1.84
  avg r-multiple       +0.42 R
  best session       London       +6,210 USD   (  7:30 - 13:00 UTC )
  worst session      Asia         -1,420 USD
  emotion tag       "patient"     72% of wins
------------------------------------------------------------------------
```

Mini equity curve (last 30 days, mocked sample, scaled):

```
  +1,200 |                                                          *
    +800 |                                                  *      *
    +400 |                                       *      *           *      *
       0 |----------------*-*-------*------*------*------*------*------*---*---*
     -400 |       *      *                                                       
     -800 |  *  *                                                              
         +----+----+----+----+----+----+----+----+----+----+----+----+----+----
          d1  d3  d5  d7  d9  d11 d13 d15 d17 d19 d21 d23 d25 d27 d29
```

---

## What is TradeSync?

TradeSync is a web-based trading journal for forex, crypto, futures, and stock traders. It auto-calculates PnL, R-multiple, win rate, and emotion-driven performance from your trade logs. Built around the loop: plan the trade, trade the plan, journal the outcome.

```
   +---------+      +---------+      +---------+
   |  plan   | ---> | execute | ---> | journal |
   +---------+      +---------+      +---------+
        ^                                |
        |                                |
        +--------------------------------+
                  iterate
```

---

## Features

```
  trade sync                                              v0.4.0
  ----------------------------------------------------------------
  [x]  auto PnL                       multi-level TP allocation
  [x]  partial take-profits           weighted R per lot share
  [x]  emotion tracking               tag every trade
  [x]  setup performance              win rate, PnL per setup
  [x]  calendar heatmap               best days, worst weeks
  [x]  reports + PDF export           equity curve, monthly P&L
  [x]  public share links             share without exposing data
  [x]  5 languages                    en, vi, ja, ko, zh
  [x]  symbol presets                 lot, fees, tick value
  [x]  market session overlay         Asia, London, NY
  [x]  daily plans + POI              bias, points of interest
  [x]  plan-aligned tracking          did entries hit a POI?
  [x]  multi-account isolation        personal, funded, paper
  [x]  minute-precision sessions      07:30, 13:45, 22:15
  ----------------------------------------------------------------
```

- **Auto PnL with partial take-profits.** Multi-level TPs allocate fees and recompute weighted R-multiple per lot share.
- **Emotion tracking.** Tag every trade with your headspace. Spot the patterns behind your worst losses.
- **Setup performance.** Win rate and PnL per setup. Cut what does not work, double down on what does.
- **Calendar heatmap.** Best days, worst weeks, missing sessions at a glance.
- **Reports with PDF export.** Equity curve, monthly P&L, top setups and symbols. Export the whole report to PDF.
- **Public share links.** Share a setup, a streak, or your equity curve without exposing your account.
- **5 languages.** English, Vietnamese, Chinese, Japanese, Korean.
- **Symbol presets.** Save default lot, fees, and tick value per instrument.
- **Market session overlay.** Sydney, Tokyo, London, New York — overlay on your trade times, minute precision.
- **Daily plans with POI.** Bias, points of interest, and sessions written before the bell.
- **Plan-aligned trade tracking.** See if entries hit a POI and ran in the right session.
- **Multi-account isolation.** Personal, funded, or paper accounts in one journal.

---

## Privacy and security

```
  data location        eu-frankfurt
  per-row isolation    every table, every row
  ad networks          none
  tracking cookies     none
  data export          json, csv
  account deletion     on request
```

- Data is stored in the EU region (Frankfurt, Germany).
- Every database table enforces row-level security tied to your account.
- No advertising, remarketing, or social media tracking cookies.
- User-controlled data export and deletion. See the privacy page for the full story.

---

## Why TradeSync

```
  +---------------------------+-----------+-----------+
  | dimension                 | typical   | TradeSync |
  +---------------------------+-----------+-----------+
  | storage region            | us        | eu        |
  | ad networks               | yes       | no        |
  | row-level security        | optional  | default   |
  | languages                 | 1-2       | 5         |
  | public share without leak | rare      | yes       |
  | minute-precision sessions | no        | yes       |
  | account deletion SLA      | unclear   | 30 days   |
  +---------------------------+-----------+-----------+
```

- **Discipline first.** Daily plans, POI tracking, and emotion tagging are designed around the plan, execute, review loop.
- **Privacy by default.** EU region, row-level security, no ad networks.
- **Multi-account.** Manage personal, funded, and paper accounts in one journal.
- **Five languages.** Built for a global trader community, not English-only.
- **Transparent.** Open privacy policy and terms of service.

---

## Get started

```
  $ open https://tradesynchub.app/signup
  $ # create account. no credit card.
  $ # log first trade.
  $ # build the daily ritual.
```

1. Go to https://tradesynchub.app/signup
2. Create your account. No credit card required.
3. Log your first trade.
4. Build the daily ritual.

---

## Links

- Web app: https://tradesynchub.app/
- Privacy policy: https://tradesynchub.app/privacy
- Terms of service: https://tradesynchub.app/terms

---

## License

Documentation in this repository is licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). No source code is published in this repository.

---

## Contact

- Web: https://tradesynchub.app/
- Email: tradesynchub.app@gmail.com
