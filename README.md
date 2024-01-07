# Healthcare_Blockchain
This repository features a Python script that simulates a smart contract for an e-commerce transaction between a buyer and a seller.

# Description

The SmartContract class in the script models a transaction where a buyer agrees to purchase a product at a specified price from a seller. It demonstrates a basic workflow of a smart contract in an e-commerce environment.
Features

    Contract initiation with specific buyer, seller, and price.
    Payment processing from the buyer.
    Delivery confirmation based on payment status.
    Transaction finalization upon complete payment and delivery.
    Contract status tracking.

# Code Structure

    __init__: Initializes the contract with default values.
    initiate_contract: Begins the contract with buyer, seller, and price.
    pay: Manages the payment from the buyer.
    deliver_item: Ensures item delivery after payment.
    finalize_transaction: Completes the transaction once all conditions are met.
    contract_status: Shows the current state of the contract.

# Usage

To use the script, create an instance of the SmartContract class and invoke its methods to simulate an e-commerce transaction.

python

contract = SmartContract()
print(contract.initiate_contract("BuyerName", "SellerName", PriceAmount))
Followed by payment, delivery, and finalization methods.
