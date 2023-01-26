# Official Documentation for the Binance APIs and Streams.
* Official Announcements regarding changes, downtime, etc. to the API and Streams will be reported here: **https://t.me/binance_api_announcements**
* Streams, endpoints, parameters, payloads, etc. described in the documents in this repository are considered **official** and **supported**.
* The use of any other streams, endpoints, parameters, or payloads, etc. is **not supported**; **use them at your own risk and with no guarantees.**


Name | Description
------------ | ------------
[errors.md](./errors.md)    | Error codes and messages of Spot API
[filters.md](./filters.md)  | Details on the filters used by Spot API
[rest-api.md](./rest-api.md)                      | Spot REST API (`/api`)
[web-socket-api.md](./web-socket-api.md)          | Spot WebSocket API
[web-socket-streams.md](./web-socket-streams.md)  | Spot Market Data WebSocket streams
[user-data-stream.md](./user-data-stream.md)      | Spot User Data WebSocket streams
&#x0020; |
[Wallet, Sub-account](https://binance-docs.github.io/apidocs/spot/en) | Details on Wallet and sub-accounts endpoints(`/sapi`)
[Margin, BLVT](https://binance-docs.github.io/apidocs/spot/en) | Details on Margin and BLVT endpoints(`/sapi`)
[Mining](https://binance-docs.github.io/apidocs/spot/en) | Details on Mining endpoints(`/sapi`)
[BSwap, Savings](https://binance-docs.github.io/apidocs/spot/en) | Details on BSwap and Savings endpoints(`/sapi`)
[USDT-M Futures](https://binance-docs.github.io/apidocs/futures/en/)  | Details on USDT-M Futures API (`/fapi`)
[COIN-M Futures](https://binance-docs.github.io/apidocs/delivery/en/) | Details on COIN-M Futures API (`/dapi`)

# FAQ


Name | Description
------------ | ------------
[spot_glossary.md](./faqs/spot_glossary.md) | Definition of terms used in the API
[trailing-stop-faq.md](./faqs/trailing-stop-faq.md)   | Detailed Information on the behavior of Trailing Stops on the API
[stp-faq.md](./faqs/stp_faq.md) | Detailed Information on the behavior of Self Trade Prevention (aka STP) on the API


# Useful Resources

* [Postman Collections](https://github.com/binance/binance-api-postman)
    * A postman collection containing the API endpoints for quick and easy use.
    * This is recommended for new users who want to get a quick-start into using the API.
* Connector
    * This is a lightweight library that works as a connector to Binance public API.
    * [Python](https://github.com/binance/binance-connector-python)
    * [Node.js](https://github.com/binance/binance-connector-node)
    * [Ruby](https://github.com/binance/binance-connector-ruby)
    * [DotNET](https://github.com/binance/binance-connector-dotnet)
    * [Java](https://github.com/binance/binance-connector-java)
    * [Rust](https://github.com/binance/binance-spot-connector-rust)
    * [PHP](https://github.com/binance/binance-connector-php)
* [Swagger](https://github.com/binance/binance-api-swagger)
    * A YAML file with OpenApi specification on the RESTful API is available to be used, as well as a Swagger UI page for the consulting.
* [Spot Testnet](https://testnet.binance.vision/)
    * Users can use the SPOT Testnet to practice SPOT trading.
    * Currently, this is only available via the API.
    * Only endpoints starting with `/api/*` are supported, `/sapi/*` is not supported.

# Contact Us

* [Binance API Telegram Group](https://t.me/binance_api_english)
    * For any questions regarding sudden drop in performance with the API and/or Websockets.
    * For any general questions about the API not covered in the documentation.
* [Binance Developers](https://dev.binance.vision/)
    * For any questions/help regarding code implementation with API and/or Websockets.
* [Binance Customer Support](https://www.binance.com/en/support-center)
    * For cases such as missing funds, help with 2FA, etc.
