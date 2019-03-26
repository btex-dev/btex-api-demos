# BTEx exchange APIs

The BTEx exchange APIs consists of the apis for public datas and apis for trading operations. 

## Public API (Public data)

| url | function | description |
| :--- | :--- | :--- |
| /openapi1/pairs | get tickers of all markets | [detail]()|
|  /openapi1/pair?pair=COIN_ANCHOR | get ticker of a single market | [detail]()|
| /openapi1/k_data/?pair=COIN_ANCHOR&k_type=TYPE&rand_key=RND | get the K-Line data | [detail]()|

## Trading API (trading operations)

For security reason, most trading apis requires the signature for every requests. You can figure out the specific [signature algorithm]()

| url | function | description |
| :--- | :--- | :--- |
| /openapi1/orderbook | get the market order book | [detail]()|
|  /openapi1/trades?pair=COIN_ANCHOR | get market trade lists | [detail]()|
| /openapi1/auth_api | operations for `get my info`, `buy`, `sell`, `get my orders`, `cancel orders`, `get my trade lists` | [detail]()|
