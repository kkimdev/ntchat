# Never Trust Chat
- Website: https://ntchat.org
- Demo: https://www.youtube.com/watch?v=hPI92JVU1ZA

This is a serverless p2p end-to-end encrypted chat app implemented in only one tiny file, [index.tml](https://github.com/kkimdev/ntchat/blob/master/index.html).  There is no external files to load, and there is no server, thus you can easily audit the code and verify that your chat is properly secured.

Caveat: p2p connection might not succeed depending on the network configuration. The most common case is that when the both clients are behind symmetric NAT, and it accounts about ~20% as of 2018-06-28.  More information: https://webrtchacks.com/symmetric-nat/