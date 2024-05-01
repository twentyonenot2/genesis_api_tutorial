### Genesis: Time Series Model for Financial Forecasting

Genesis is a pre-trained time series model that uses OHLC prices and a proprietary price volatility feature to forecast an underlying asset's price trend. The proprietary volatility feature provides a directional context to the time series. 

The model produces a directional price forecast and risk forecast that identifies a price boundary within which the underlying asset's price should close for the direction forecast to remain true.

#### Proprietary Price Volatility Transformer
Genesis leverages a proprietary price volatility transformer to incorporate the long-term directional price volatility context, enhancing its understanding of financial time series data within a defined context window.

#### Zero-Shot Forecasting Capabilities
With its unique volatility feature, Genesis can perform zero-shot forecasting of the underlying asset's price trend. This forecasting capability spans across multiple asset classes, from tick frequency data to forecasts several weeks ahead.

#### Navigate Market Volatility 

Through forecasts over different time horizons, Genesis can deliver real-time insights and an understanding of how prices are changing, enabling users to uncover temporal relationships and dependencies that exist to anticipate market shifts. 

#### Minimum Data Requirements
To generate one-step-ahead forecasts, Genesis requires a minimum of 400 complete OHLC (open, high, low, close) periods of historical data. 

