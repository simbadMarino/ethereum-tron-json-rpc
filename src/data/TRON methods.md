### Missing or limited eth-json-rpc methods on TRON

| method                                | ****limitation****    | caused by                                                                         |
| ------------------------------------- | --------------------------------- | --------------------------------------------------------------------------------- |
| `eth_getBalance`                    | only "latest" block is available | No `stateRoot` available in header, sate trie needed                           |
| `eth_getCode`                       | only "latest" block is available | No `stateRoot` available in header, sate trie needed                           |
| `eth_getStorageAt`                  | only "latest" block is available | No `stateRoot` available in header, sate trie needed                           |
| `eth_call`                          | only "latest" block is available | No `stateRoot` available in header, sate trie needed                           |
|                                       |                                   |                                                                                   |
| `eth_getProof`                      | Not available in TRON             | Most likely `stateRoot` related                                                 |
| **`eth_getTransactionCount`** | Not available in TRON             | Most likely `stateRoot` related                                                 |
| `eth_getUncleCountByBlockNumber`    | Not available in TRON             | TBD                                                                               |
| `eth_getUncleCountByBlockHash`      | Not available in TRON             | TBD                                                                               |
| `eth_getUncleByBlockNumberAndIndex` | Not available in TRON             | TBD                                                                               |
| `eth_getUncleByBlockHashAndIndex`   | Not available in TRON             | TBD                                                                               |
| `debug_traceCall`                   | Not available in TRON             | Implementation[in progress](https://github.com/tronprotocol/java-tron/issues/5778)   |
| `debug_traceTransaction`            | Not available in TRON             | No debug methods in TRON node yet                                                 |
| `debug_traceBlockByNumber`          | Not available in TRON             | No debug methods in TRON node yet                                                 |
| `debug_traceBlockByHash`            | Not available in TRON             | No debug methods in TRON node yet                                                 |
| `eth_getBlockReceipts`              | Not available in TRON             | Implementation[in progress ](https://github.com/tronprotocol/java-tron/issues/5910) |
| `trace_block`                       | Not available in TRON             | No trace methods in TRON node yet                                                 |
| `trace_call`                        | Not available in TRON             | No trace methods in TRON node yet                                                 |
| `trace_filter`                      | Not available in TRON             | No trace methods in TRON node yet                                                 |
| `trace_rawTransaction`              | Not available in TRON             | No trace methods in TRON node yet                                                 |
| `trace_replayBlockTransactions`     | Not available in TRON             | No trace methods in TRON node yet                                                 |
| `trace_replayTransaction`           | Not available in TRON             | No trace methods in TRON node yet                                                 |
| `trace_transaction`                 | Not available in TRON             | No trace methods in TRON node yet                                                 |
