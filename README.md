Description

The script includes classes to represent patient records (PatientRecord) and blockchain blocks (Block). Each block in the blockchain contains a patient record, ensuring the integrity and traceability of medical data.
Features

    Patient Record Management: Handles patient data including ID, name, and medical information.
    Blockchain Implementation: Securely stores patient records in an immutable blockchain structure.
    Data Integrity: Each block is hashed to ensure data integrity, with references to the previous block.

Code Structure

    PatientRecord: Represents a patient's medical record.
    Block: Represents a block in the blockchain, containing a patient record.
    calculate_hash: Generates a hash for each block based on its contents.
    create_genesis_block: Creates the initial block in the blockchain.
    create_new_block: Adds new blocks to the blockchain with patient records.
    Main Execution: Demonstrates adding records and prints the blockchain details.

Usage

To use the script, instantiate PatientRecord objects and add them to the blockchain using the create_new_block function.
Disclaimer

This code is a conceptual representation for educational purposes. It is not intended for real-world medical data management or any production use.
