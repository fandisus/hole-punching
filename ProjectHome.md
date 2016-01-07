This is a C# library that manage TCP and UDP Hole Punching feature for NATted hosts.

Brief summary: Hole Punching is a technique that allow two NATted hosts to talk each other directly without the presence of an external server (but it is necessary for some of the first step). This trick is possible only if both hosts are behind a symmetric NAT, that assign the same source port for all the outgoing packets with the same remote endpoint (IP:Port).
Obviously this technique is useless (even if it can be used anyway) if one or both hosts are not behind a NAT and thus they are directly reachable over the Internet.