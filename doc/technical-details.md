StartCOIN [START] Technical Details
===================================

This document outlines the technical implementation details for StartCOIN. It should be of use to advanced users and developers.

Specifications
--------------

* XXX coins in total
* 1 minute block time
* XXX coins per block
* Block reward halves ever XXX
* Retargets difficulty using Kimoto Gravity Well

Port numbers
------------

The following port numbers are used by StartCOIN.

* P2P uses port 57467 (67467 on Testnet)
* RPC uses port 57477 (67477 on Testnet)

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
