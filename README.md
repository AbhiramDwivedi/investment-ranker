# investment-ranker

The published pages for a personal stock-research tool.

**→ [The Ranker](https://abhiramdwivedi.github.io/investment-ranker/)** — updated every weekday
evening after the U.S. close.

**→ [Method note](https://abhiramdwivedi.github.io/investment-ranker/approach.html)** — what the
numbers mean, what the backtests found, and what the screen cannot see.

## What this is

A nightly screen of the S&P 1500 for companies trading cheap **against their own ten-year valuation
history** — not against their peers, and not merely down from a high. Every S&P 1500 name with an SEC
filing history is scored by the same code, from SEC EDGAR company facts and daily prices.

The honest summary of the backtest is on the unflattering side: the rule **alone has no edge** against
the index. Two valuation bases agreeing, and a market that is itself on sale, do carry information. The
method note shows the numbers that say so, including the ones that argue against the premise.

## What this is not

**This is not investment advice, and nothing here is a recommendation to buy or sell any security.**
It is one person's research tool, published because the reasoning is more useful in the open than in a
private file. A name appearing on this page means "worth reading about," never "worth buying."

There are no holdings, positions, account values or personal data on these pages, by design and by an
automated check that refuses to publish if any appear.

## How it gets here

This repository holds only the rendered output. The engine, its data and its backtests live in a
separate private repository; a nightly job renders these two pages and pushes them here.

Figures carry the date of the market close they were built from.
