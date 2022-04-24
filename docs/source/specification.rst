Specification
=============

In an economic sense a transaction means the delivery of a services S by Entity A, and payment of the that service by Entity B, the Customer. It is worthwhile pointing out that this general description of a commercial transaction is in fact made up of a series of actions (sub-transactions) based on several data points. The fundamental difference between the traditional way of recording a commercial transaction and of recording in the newly proposed blockchain-based method is that in the traditional way, the transactions are recorded independently in each participant's database record, and from there, the information is fed into their separate financial reporting systems. In the proposed system, however, the commercial transaction details are directly written into the blockchain, with participants now having access to details from the same source. The information is then fed into each participant’s database and reporting system. In this way, the likelihood of mismatching transaction information is diminished as the information is fed from the same source. 

.. _data_parameters:

Data parameters 
----------------

Data parameters needed to model the proposed process of executing economic transaction:
 - :ref:`Participants`
 - :ref:`Product/Service`
 - :ref:`Acceptance of Product/Service`
 - :ref:`Payment`
 - :ref:`Supporting documents`
 - :ref:`Supplier information`
 - :ref:`Customer information`
 - :ref:`Product/Service`



.. _participants:

Participants 
-------------

- ``EA``:  unique description of entity A, the Supplier.
- ``EB``: unique description of entity A, the Customer.

.. _product_and_service:

Product/Service
---------------

- ``PSDesc``: this data describes the specific product or services subject to the transaction. 
- ``TAmt``: this data identifies the total estimated amount of the transaction for the delivery of goods or services; this amount is stipulated in the contract between entities A and entity B.
- ``TPS``: this data identifies the transaction amount associated with the delivery of a product or service at a specific point in time; note that this amount may be different from the agreed amount of the transaction in case of partial delivery of products or service.
 
.. _acceptance_of_product_and_service:

Acceptance of Product/Service
---------------
- ``AD``: **Acceptance Document.** This is confirmation typically done in writing signed by the Entity B who acknowledging to Entity A the receipt of products, or the conformity of the receiving the services in accordance with the agreed terms of the transaction.

.. _payment:

Payment
-------
- ``TP``: Transaction payment or transaction settlement amount. Participants in a transaction pay typically in fiat money for the delivery of a certain product or services by means of a bank payment order or credit card. As an alternative, in a blockchain setting, this settlement can be done using tokens or cryptocurrencies such as Bitcoin or Ethereum. Note that this amount may be different from TS invoiced by the EA in case of partial payment. 

.. _supporting_documents:

Supporting documents
-------
- ``Invoice``: When a product is delivered or a service is rendered, the Entity A issue an invoice including the following data points:
- etc etc

.. autosummary::
   :toctree: generated

   lumache
