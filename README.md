> "A trip to the moon requires a rocket with multiple stages or otherwise the rocket equation will eat your lunch..." -- nullc, [2016-01-29](https://www.reddit.com/r/Bitcoin/comments/438hx0/a_trip_to_the_moon_requires_a_rocket_with/)

A collection of analysis about Bitcoin second-layers protocols's security and performance with regards to their base layer interactions. The purpose of this documentation is to spread knowledge of L2's
onchain security and perfomance open problems among the Bitcoin protocol dev community and hopefully to assist in the design of solutions.

The first [section](threats/README.md) repertories the list of known attacks against L2s, especially the class of attacks known as tx-relay jamming exploiting p2p and mempool acceptance rules against multi-party contract
protocols.

The second [section](performance/README.md) relates the performance of L2s in matters of fee-bumping, cooperative opening/closing dust selection, rebroadcasting, etc. It aims to illustrate how L2s are consuming base layers resources
such as blockspace, bandwidth, utxo sets, mempool space, etc and trade-offs to think about while suggesting improvements.

The third [section](protocols/README.md) provides a survey of major L2 protocols architecture and onchain operations. Further, it precises per-protocol the vulnerabilites and performance issues affecting them. It also points towards
known implementations and standards of each of them.

The last [section](discussions/README.md) submit to the dev community a list of discussions/questions about potential solutions to problems raised in the first sections.

Finally, a serie of [workshops](workshops/) are organized to foster discussions and developements in those areas.

Feel free to contribute :)

Licensed under Apache 2.0
