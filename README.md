# DAppNode package Web3signer Lukso

A validator client contributes to the consensus of the Eth2 blockchain by signing proposals and attestations of blocks, using a BLS private key which must be available to this client at all times.

The BLS remote signer API is designed to be consumed by validator clients, looking for a more secure avenue to store their BLS12-381 private key(s), enabling them to run in more permissive and scalable environments.

More information about the EIP can be found at the official website

Why Web3signer ?
Client diversity is a key path in DAppNode, you will be able to use different clients and do not deposit all the trust on just one of them. It can work as a load balancer, keeping your validators always validating

Select the Web3Signer package as part of your configuration in the Stakers tab of the Dappmanager.
