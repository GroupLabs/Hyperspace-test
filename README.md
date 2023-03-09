# Hyperspace

A cross-platform application that enables augmented reality experiences while minimizing friction to entry. This is done by providing as much support to as many devices possible, and reducing commitments on the user end (like not having to download an entire application before using).

Our goal is to let people come across AR experiences from anywhere.

## Development

```mermaid
flowchart TD
  subgraph Map
   Unity --> ios[ARKit]
   Unity --> android[ARCore] 
  end