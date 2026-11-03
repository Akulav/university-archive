# RTP Lab 2: Persisting the Stream to MongoDB

Builds on [RTP-LAB1](../RTP-LAB1). Analysed tweets are collected by a sink and written to MongoDB in batches.

## Features

- Everything from Lab 1 (router, supervised workers, sentiment analysis)
- A sink that buffers results and flushes them when a batch is full or a timeout fires
- MongoDB connection for storing results

## Running

Start a MongoDB instance first, then:

```bash
mix deps.get
mix run --no-halt
```
