## Quantitative equity strategies

`Quantitative equity` is generally used to describe hedge funds which target longer time horizons (`weeks, months, years`) and use quantitative methods and statistics to find signals to trade. In quantitative equity, signals are generally much weaker than those that can be seen in high frequency trading, due to the increased noise of longer time horizons.

Rather, quantitative equity is a game of
1. **Size**: with large pools of client money
2. **Diversity**: with very large universes of stocks to invest in

At many quant equity shops, signals are combined to predict excess returns; `AQR` is an excellent example of this, particularly because they publish their white papers for the public.

### Results

#### Value

#### Growth

#### Momentum

### Fund aims, universe, benchmark and time horizon

- Universe: `S&P 500`
- Benchmark: `S&P 500`
- Rebalancing frequency: `Monthly`, targeting `1-month` horizons

### Data sources

Unfortunately, a portion of this project will not be able to be run by the general public due to data licensing issues. You can source your own data, and create your own data tables (with the tables I have stored in `data`) or take the results at face value. I will say that:
- I am a little suspect about any look-ahead biases in our fundamental data.
- I am *not* an expert at factor models, and this is my first exposure to factor models

I have read papers and tried to find the industry-norm when applying any methods to factor calculation and composition.

For stock-pricing data, however, I suggest you look at my `stat-arb-in-us-equities` project and it's data filling to get constituents for the `S&P 500` as well as getting daily pricing (and then aggregating to weekly and monthly prices).

