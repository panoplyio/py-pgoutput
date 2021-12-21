# Python Decoder for pgoutput adapter

* Used for PSQL CDC
* Decodes every type of logical replication message: ```'B', 'C', 'O', 'R', 'Y', 'I', 'U', 'D', 'T'```
* Algorithm of decoding is specified here: [link](https://www.postgresql.org/docs/12/protocol-logicalrep-message-formats.html)
* More about how to track changes overall: [link](https://medium.com/@film42/getting-postgres-logical-replication-changes-using-pgoutput-plugin-b752e57bfd58), [link](https://www.npgsql.org/doc/replication.html)
