# P2P

!!! info
    P2P blocking rules available at [{{ config.repo_url }}tree/master/data/p2p]({{ config.repo_url }}tree/master/data/p2p)

The [P2P data format](https://en.wikipedia.org/wiki/PeerGuardian#P2P_plaintext_format) is the original format for
PeerGuardian version 1.x and can be used with [PeerBlock](https://sourceforge.net/projects/peerblock),
[PeerGuardian](http://sourceforge.net/projects/peerguardian/), [iplist](http://iplist.sourceforge.net/) and many others.

You can integrate data specifically generated in the P2P format by copying the content of a `.txt` file located
in `data/p2p`.

Here is an example with PeerBlock and the data from `data/p2p/spy.txt`:

![](../assets/blocking-rules/p2p/p2p-win10-spy.png)
