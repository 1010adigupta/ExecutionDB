## ExecutionDB: LSM-tree Storage Engine for Blockchain Execution Clients
A high-performance storage engine optimized for blockchain execution clients, featuring LSM-tree (Log-Structured Merge-tree) architecture with specific optimizations for blockchain workloads.
### Key Features

**Optimized for Blockchain State:** Efficient storage and retrieval of account states, storage tries, and block data

**Multi-versioned State Management:** Maintains historical states with minimal overhead

**Concurrent Access:** Lock-free read operations with MVCC (Multi-Version Concurrency Control)

**Fast Recovery:** Quick restart and recovery mechanisms for chain reorganizations

**Pruning Support:** Configurable state pruning with customizable retention policies

**Memory-mapped I/O:** Zero-copy reads for frequently accessed data

**Compaction Strategies:**
Level-based compaction optimized for blockchain state transitions
Background compaction with minimal impact on read performance
Smart compaction scheduling based on block finality
