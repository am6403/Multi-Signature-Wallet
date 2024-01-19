# Multi-Signature-Wallet
A multi-signature wallet is a digital wallet designed to enhance security by requiring multiple private keys to authorize and execute transactions. Unlike traditional single-signature wallets that rely on a single key for access, multi-signature wallets distribute control among multiple parties. Common configurations include 2-of-3 or 3-of-5, where a specified number of private keys from the total set are required to validate a transaction. The added security layer ensures that a predetermined number of keys must match for a transaction to be successfully executed.

Steps:-

1)Deployment: During the deployment process, input the addresses of the owners who will have control over the multi-signature wallet.
2)Setting Required Confirmations: Specify the required number of confirmations for a transaction to be considered valid. This ensures that more than the specified number of owners must approve a transaction.
3)Transaction Details: Input the details of the transaction, including the amount of Ether to be transferred.
4)Confirmation by Owners: The owners must confirm the transaction by individually accepting or rejecting it. If all owners accept, the Ether transfer proceeds; otherwise, it is canceled.
5)Auto-Transfer on Confirmation: If the required number of confirmations is reached, the balance designated for the transaction is automatically transferred.
6)Automatic Rejection: If the required number of confirmations is not met within the set limit, the transaction is automatically rejected, and the balance remains unchanged.
