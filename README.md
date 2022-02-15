# mermaid-test
A simple test of the mermaid functionality of in GitHub render


## TCP three-way handshake
```mermaid
sequenceDiagram
    participant s as Sender
    participant r as Reciever
    Note left of r: A diagram of the TCP three way handshake
    s ->> r Send SYN message
    r ->> s: response SYN/ACK
    s ->> r: respond with ACK

```