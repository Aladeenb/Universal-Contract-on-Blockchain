# Design and Implementation Constraints

The design is simple and because of the simplicity it is not so complicated when it comes to designing. Implementation has its constraints.

* Solidity is a limited language because it is built on top of something that has limitations for security reasons.
* Transactions are not allowed to be signed before runtime. This creates a huge problem as this system should be automatic when it comes to recurring payments.
* Sender should always be the supplier in the early development stages as this will complicate things because of the principles of blockchain. Users need the have the image in their head that when they sign their wallet is being used as a tool to identify them and this could only be done if they are the supplier.
