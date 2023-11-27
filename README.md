# CH_Scaled

**The task:** Create a platform for fast technical chart analysis. It should work on large lists of assets in one click.

**The solution:** We've created a platform which finds stocks, crypto and other assets in good technical position (for example, oversold). The platform works in one click and spends about 8 seconds for 1 asset.

CH loads data from <ins>few APIs</ins>. It's easy to write a script for any new source of OHCL (open, low, high, close) data. The length of OHCL list is customizable.

<ins>The algorithm</ins> of Candle Handle takes data as OHLC format and returns it's evaluation. The algorithm consists of two main parts:

1. Find charts which are close to our schema. The schema of chart is customizable. 
2. Find charts where positive market sentiment is stronger than negative. Some parameters are also customizable.

Besides that, CH has some <ins>secondary features</ins>, like <i>"rank all assets by evals"</i> or <i>"rank all assets by anomality"</i>.

Overall, CandleHandle is quite simple yet powerful tool for fast technical analysis of large lists of assets. It won't make you rich, but can significantly improve your efficiency on markets. If it's used wisely!

**Current version:** <ins>CandleHandle Scaled 1.0.0.</ins> CH_Scaled has it's own version number since 27.11.2023

**Updates:** Coming soon...

**Disclaimer**: <i>CandleHandle analysis is not a personal investment advice. You should manage your risks carefully, the author and developers is not responsible for your losses!</i>
