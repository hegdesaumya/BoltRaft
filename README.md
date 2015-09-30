BoltDB

Bolt is a pure Go key/value store. It is stable and the API is fixed. Full unit test coverage and randomized black box testing are used to ensure database consistency and thread safety. Bolt is currently in high-load production environments serving databases as large as 1TB. Many companies such as Shopify and Heroku use Bolt-backed services every day.

RAFT

Raft is a consensus algorithm that is designed to be easy to understand. It's equivalent to Paxos in fault-tolerance and performance. The difference is that it's decomposed into relatively independent subproblems, and it cleanly addresses all major pieces needed for practical systems. We hope Raft will make consensus available to a wider audience, and that this wider audience will be able to develop a variety of higher quality consensus-based systems than are available today.

Repository

Idea behind this repository is to implement RAFT over BoltDB in distributed environment to address Replication and Fault Tolerance issues of BoltDB.
