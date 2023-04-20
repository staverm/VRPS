# Verifiable Random Peer Sampling
Verifiable Random Peer Samplers (VRPSs) are a novel class of peer sampling protocols aimed at providing defense for large-scale public blockchains against network attacks.

This work formally introduces VRPSs, provides a general framework for implementing a VRPS, explores various distributed systems models in which this framework can be applied, and discusses potential implementation techniques.

Our primary contribution is **Ora**, a first in the line of, hopefully many, VRPSs. Ora operates within the Oracle model, which defines two roles: sampling oracles, responsible for providing peer samples, and clients that request samples from oracles. We consider a strong adversary, achieving safety in the Anytrust model, which merely assumes that at least one sampling oracle in the entire network is honest.

Discover more in the provided paper!
