### Missing or limited eth-json-rpc methods on TRON

| method                                | limitation                        | root cause                                              | Needed for | Prio |
| ------------------------------------- | --------------------------------- | ------------------------------------------------------- | ---------- | ---- |
| `eth_getBalance`                    | only "latest" block is available | No `stateRoot` available in header, sate trie needed |            |      |
| `eth_getCode`                       | only "latest" block is available | No `stateRoot` available in header, sate trie needed |            |      |
| `eth_getStorageAt`                  | only "latest" block is available | No `stateRoot` available in header, sate trie needed |            |      |
| `eth_call`                          | only "latest" block is available | No `stateRoot` available in header, sate trie needed |            |      |
| `eth_getLogs`                       | research more                     | TBD                                                     |            |      |
| `eth_getProof`                      | Not available in TRON             | Most likely `stateRoot` related                       |            |      |
| **`eth_getTransactionCount`** | Not available in TRON             | Most likely `stateRoot` related                       |            |      |
| `eth_getUncleCountByBlockNumber`    | Not available in TRON             | TBD                                                     |            |      |
| `eth_getUncleCountByBlockHash`      | Not available in TRON             |                                                         |            |      |
| `eth_getUncleByBlockNumberAndIndex` | Not available in TRON             |                                                         |            |      |
| `eth_getUncleByBlockHashAndIndex`   | Not available in TRON             |                                                         |            |      |
| `debug_traceCall`                   | Not available in TRON             |                                                         |            |      |
| `debug_traceTransaction`            | Not available in TRON             |                                                         |            |      |
| `debug_traceBlockByNumber`          | Not available in TRON             |                                                         |            |      |
| `debug_traceBlockByHash`            | Not available in TRON             |                                                         |            |      |
|                                       |                                   |                                                         |            |      |
