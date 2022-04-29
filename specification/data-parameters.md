---
description: >-
  Data parameters needed to model the proposed process of executing economic
  transaction
---

# Data Parameters

## **Universal Contracts**

### Participants

#### EA

unique description of entity A, the Supplier

EB

unique description of entity A, the Customer

### Product/Service

#### PSDesc

this data describes the specific product or services subject to the transaction.

#### TxAmt

this data identifies the total estimated amount of the transaction for the delivery of goods or services; this amount is stipulated in the contract between entities A and entity B.

#### Dt

this date describes the duration of the contract.

#### TxPS

this data identifies the transaction amount associated with the delivery of a product or service at a specific point in time; note that this amount may be different from the agreed amount of the transaction in case of partial delivery of products or service.

#### TxType&#x20;

this data identifies the type of transactions (e.g., recurring, or one-off).

#### TxInd

this data describes the supplier industry (e.g., lease, insurance)

#### Term

this data will include critical information (e.g. applicable law) which cannot be numerically or Boolean-format parametrized.&#x20;

## **Invoice**

### Supplier information

#### EA

unique name of the supplier of goods or services**.**

#### EATradeReg

unique identification number issued by the Trade Registry**.**

#### EAVATNo

unique identification number (VAT) with the Fiscal Authorities**.**

#### EA-IBAN

This is the unique bank account number of EA; payment is done by the EB bank account into this bank account**.**

### Customer information:

#### EB

unique name of the supplier of goods or services**.**

#### EBTradeReg

unique identification number issued by the Trade Registry

#### EBVATNo

unique identification number (VAT) with the Fiscal Authorities.

#### EB-IBAN

This is the unique bank account number of EA; payment is done by the EB bank account into this bank account.

### Product/Service

#### TPSDesc

Transaction product/service description. This data describes the product delivered or service rendered; this description should be the same as PSDesc.

#### TPS

Actual amount of the transaction for the delivery of goods or rendering of services.

#### VATAmt

On top of the TPS, a certain percentage is added representing the Value Added Tax (19% in Romania with some exceptions, 21% average of the EU countries).

#### TPSinclVAT

This is the total amount of the actual transactions including the VAT percentage.

## **Payment (Digital Wallets)**

#### TxP

Transaction payment or transaction settlement amount. Payments are executed using specific blockchain digital wallets. Participants in a transaction pay typically in fiat money for the delivery of a certain product or services by means of a bank payment order or credit card. As an alternative, in a blockchain setting, this settlement can be done using tokens or cryptocurrencies such as Bitcoin or Ethereum. Note that this amount may be different from TS invoiced by the EA in case of partial payment.

## **Supporting Documents (Acceptance of Product/Service)**

#### AD

Acceptance Document. This is confirmation typically done in writing signed by the Entity B who acknowledging to Entity A the receipt of products, or the conformity of the receiving the services in accordance with the agreed terms of the transaction. Acceptance or rejection of services is relayed into the blockchain as a message transaction type.
