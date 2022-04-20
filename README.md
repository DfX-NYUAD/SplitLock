SplitLock

Related to A. Sengupta, M. Nabeel, J. Knechtel, and O. Sinanoglu, “A New Paradigm in Split Manufacturing: Lock the FEOL, Unlock at the BEOL,” in Proc. Design Automation and Test in Europe (DATE), pp. 414-419, 2019 (DOI: 10.23919/DATE.2019.8715281) (https://arxiv.org/pdf/1903.02913.pdf)

The benchmarks are post-processed to work with the network flow attack provided in [1]. As the attack cannot process tie cells, we replace the tie cells with buffers which are driven from primary ports containing the correct key value. To make sure fair evaluation, we route the nets connecting the ports to buffers entirely in the FEOL, whereas the nets from buffers to key-gates are explicitly lifted to BEOL.

The correct key values are contained in the names, e.g. logic_x means the correct key value is x.

[1] Yujie Wang, Pu Chen, Jiang Hu, Guofeng Li, Jeyavijayan Rajendran, "The Cat and Mouse in Split Manufacturing", TVLSI'18.
