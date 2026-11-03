# PR Lab 1: Multithreaded Data Crawler

A C# console app for a network programming lab. It crawls a local test server, converts the data it finds, and serves the results over TCP.

## What it does

1. Registers with the server at `http://localhost:5000/register` to get an access token.
2. Starting from `/home`, follows links using a thread pool.
3. Downloads records in **JSON, XML, YAML and CSV** and converts them all to one JSON format.
4. Opens a TCP server on port **9999**. Connect with telnet to query the collected data. Once a client connects, the crawler threads stop.

## Dependencies

NuGet packages: `Newtonsoft.Json`, `YamlDotNet`, `ChoETL`.

## Running

1. Start the lab's test server on `localhost:5000`.
2. Create a .NET console project with `Application.cs`, add the packages above, and run it.
3. Connect with:

```bash
telnet localhost 9999
```
