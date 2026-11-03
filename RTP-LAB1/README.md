# RTP Lab 1: Stream Processing with Elixir

A real-time programming lab. It reads a stream of tweets and runs sentiment analysis on them with a supervised pool of workers.

## Features

- 4 workers (easy to scale) that receive messages round-robin from a router
- Failed workers are restarted automatically by their supervisor
- Sentiment analysis of each tweet using a word-score list
- Prints each tweet with its sentiment score

## Running

```bash
mix deps.get
mix run --no-halt
```

`--no-halt` keeps the VM running after startup so the application can keep processing the stream.
