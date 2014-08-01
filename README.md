## Node.js CQL Driver for Apache Cassandra ##

This is a fork of [node-cassandra-cql](https://github.com/jorgebay/node-cassandra-cql) that includes
[Kit Cambridge's normalize-typed-value-v1 branch](https://github.com/kitcambridge/node-cassandra-cql/tree/normalize-typed-value-v1)
that is required to properly support `map` types under the binary v1 protocol.

**This repository was specifically created to support the [priam](https://github.com/godaddy/node-priam) library without requiring a
GitHub dependency under NPM.**
