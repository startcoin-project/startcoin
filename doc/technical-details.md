StartCOIN [START] Technical Details
===================================

This document outlines the technical implementation details for StartCOIN. It should be of use to advanced users and developers.

Specifications
--------------

* 84 million coins in total
* 1 minute average block time
* 40 coins per block
* Block reward halves every 12 months
* Retargets difficulty temporally using DigiShield
* x11 ASIC-resistant Proof-of-Work algorithm

Port numbers
------------

The following port numbers are used by StartCOIN.

* P2P uses port 9247 (19247 on Testnet)
* RPC uses port 9347 (19347 on Testnet)

Message start string
--------------------

The message start string used by StartCOIN is:

```
0xff, 0xc4, 0xba, 0xdf
```

The message start string for Testnet is:

```
0xff, 0xc4, 0xb9, 0xde
```
