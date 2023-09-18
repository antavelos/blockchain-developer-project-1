# Udacity | Blockchain Developer nano-degree | Project 1 | Private Blockchain Application

> The app was tested with `NodeJS v18.13.0` and `npm v9.2.0`

The following sections depict the results of the requested tests:

### Retrieve the genesis block
> `Request: http://localhost:8000/block/height/0`

![Request: http://localhost:8000/block/height/0 ](images/get_genesis_block.png)


### Request validation
> `Request: http://localhost:8000/requestValidation`

![Request: http://localhost:8000/requestValidation](images/post_request_validation.png)


### Sign message with wallet
![Sign message](images/sign_message.png)


### Submit star
> `Request: http://localhost:8000/submitStar`

#### Successful request
![Request (successful): http://localhost:8000/submitStar](images/submit_star.png)

#### Failed request: elapsed time more than 5 minutes
![Request (failed - elapsed time more than 5 minutes): http://localhost:8000/submitStar](images/submit_star_elapsed_time_more_than_5min.png)

#### Failed request: not veriafiable message
![Request (failed - not veriafiable message): http://localhost:8000/submitStar](images/submit_star_not_verifiable_message.png)


### Retrieve stars owned by a particular address
> `Request: http://localhost:8000/blocks/1S4Zg6nwypHGmbpo6hTtdC6QiTtwJwZR2`

![Request: http://localhost:8000/blocks/1S4Zg6nwypHGmbpo6hTtdC6QiTtwJwZR2](images/retrieve%20stars.png)


### Validate blockchain
> `Request: http://localhost:8000/chain/validate`

![Request: http://localhost:8000/chain/validate](images/chain_validation.png)
