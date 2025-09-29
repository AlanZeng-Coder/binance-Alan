# My Binance SDK

A simple SDK to fetch daily K-line data from Binance.US.

## Installation

```bash
pip install Alan-binance-sdk
```

```python
from Alan-binance-sdk import BinanceDataFetcher

fetcher = BinanceDataFetcher(output_dir='data')
fetcher.get_daily_klines_as_file(
    symbol_name='bitcoin',
    date_str='2025-09-28',
    output_format='csv'
)
```