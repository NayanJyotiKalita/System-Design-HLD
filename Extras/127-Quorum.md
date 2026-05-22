# Quorum

Problem statement
In a distributed system, what is the purpose of using a write quorum?

Options: Pick one correct answer from below

To reduce write latency

To ensure that a write operation is acknowledged by a majority of nodes

To optimize read performance

To manage schema migrations

Solution description
*2* --> A write quorum ensures that a write operation is only considered successful if it is acknowledged by a majority of nodes, providing consistency.