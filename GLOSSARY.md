# Systems Engineering Glossary: CRDT Collaborative Editor Core

### CRDT
Conflict-free Replicated Data Type; data structure mathematically guaranteeing eventual convergence across distributed replicas without coordination.

### Lamport Timestamp
Logical clock mechanism capturing casual ordering and break ties among concurrent operations.

### State-Based CRDT
Replication model synchronizing complete monotonic states rather than discrete delta operations.

### Causal Tree
Tree representation of collaborative text where inserted character nodes reference parent anchors.
