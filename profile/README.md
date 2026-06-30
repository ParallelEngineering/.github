# Welcome to Parallel Engineering

Parallel Engineering builds small, focused C++ projects around cryptography, large-number arithmetic, and client/server applications.

The current project family is centered on RSA: a custom Base-256 library, an RSA implementation and an messenger client/server application using RSA-based concepts.


## Project Relationships

```mermaid
flowchart TD
    Base256["Base256"]
    RSA["RSA"]
    Messenger["Messenger"]

    Base256 --> RSA
    RSA --> Messenger

    click Base256 "https://github.com/ParallelEngineering/Base256"
    click RSA "https://github.com/ParallelEngineering/RSA"
    click Messenger "https://github.com/ParallelEngineering/Messenger"
```
