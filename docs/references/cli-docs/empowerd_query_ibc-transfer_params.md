## empowerd query ibc-transfer params

Query the current ibc-transfer parameters

### Synopsis

Query the current ibc-transfer parameters

```
empowerd query ibc-transfer params [flags]
```

### Examples

```
empowerd query ibc-transfer params
```

### Options

```
      --grpc-addr string   the gRPC endpoint to use for this chain
      --grpc-insecure      allow gRPC over insecure channels, if not TLS the server must use TLS
      --height int         Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help               help for params
      --node string        \<host\>:\<port\> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
  -o, --output string      Output format (text|json) (default "text")
```

### SEE ALSO

* [empowerd query ibc-transfer](empowerd_query_ibc-transfer.md)	 - IBC fungible token transfer query subcommands

