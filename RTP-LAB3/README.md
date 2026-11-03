# RTP Lab 3: Message Broker

Builds on [RTP-LAB2](../RTP-LAB2). Processed data is encoded and sent over TCP to a message broker, which broadcasts it to connected clients.

## Structure

| Folder | Description |
| --- | --- |
| `/` (root) | The producer: stream processing pipeline plus a TCP sender (`lib/tcpsender.ex`) |
| `broker/` | TCP server that accepts connections and broadcasts incoming messages to all clients |
| `client/` | A simple TCP client that connects to the broker and receives messages |

## Running

Start each part in its own terminal, in this order:

```bash
cd broker
mix run --no-halt
```

```bash
cd client
mix run --no-halt
```

```bash
mix deps.get
mix run --no-halt
```
