# mermaid-test
A simple test of the mermaid functionality of in GitHub render

```mermaid
sequenceDiagram
    participant Sender
    participant Reciever
    sender ->> reciever: Send SYN message
    reciever ->> sender: response SYN/ACK
    sender ->> reciever: respond with ACK

```