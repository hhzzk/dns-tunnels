# dns-tunnels

This script is used to detect [DNS tunnels](http://heyoka.sourceforge.net/heyoka-shakacon2009.pdf),  and written according to the paper [_Chimera: A Declarative Language for Streaming Network Traffic Analysis_](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final116.pdf) and the report [_Detecting DNS Tunneling_](https://www.sans.org/reading-room/whitepapers/dns/detecting-dns-tunneling-34152).

It based on the count of the DNS query in a period time, the length of the DNS query, and the percentage of the numerical characters in the DNS query.

This rep is used for [Bro package](https://github.com/hhzzk/packages).
