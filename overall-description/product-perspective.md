# Product Perspective

The universal smart contract we imagine is stripped down to be the simplest version of itself. There are some aspects to be captured in this matter

o   **Supplier Information**

In a blockchain system this only means the public address of the supplier. The name of the supplier could also be used but it would be ok to keep this field optional since this doesn’t necessarily define the user in a unique way

&#x20;

o   **Customer Information**

Yet again in this environment the public address of the supplier is needed to identify where the payment/tokens come from. As stated above the name could also be kept optional.

&#x20;

o   **Duration of the contract**

The duration for which the contract is valid from and until. We need to know how long the contract will hold its validity and act rather make the payments accordingly. This means blocking some payments if they are not due or taking another course of action if they are overdue

&#x20;

o   **Amount to be paid each month**

This parameter is crucial for the smart contract to calculate the total payment as well as knowing how much or rather how many tokens to charge each recurring month. Instead of making the supplier entering the entire amount during the duration of the contract (duration of the contract \* monthly payment) we will let them enter the monthly payment and calculate the rest when we serve that information to the end user
