Actors:

Manufacturer : Represents the entity that manufactures drugs.
Distributor : Represents the entity that distributes or ships drugs.
Pharmacy : Represents the entity that sells drugs to customers.
Customer : Represents the end customer purchasing the drugs.
Regulator : Represents the regulatory authority that ensures the integrity and legality of the supply chain.

Use Cases:

Create Genesis Block : The initial block of the blockchain, setting up the chain.
Add New Transaction : Represents the action of adding new transactions (e.g., manufacturing, shipping, selling, purchasing) to the blockchain.
Validate Blockchain : The process of verifying the integrity of the blockchain, ensuring it hasn't been tampered with.
View Blockchain : Allows actors to view the entire blockchain, including all transactions.
Relationships:

Each actor interacts with the "Add New Transaction" use case to log their actions (manufacturing, shipping, selling, purchasing) into the blockchain.
The "Regulator" actor interacts with the "Validate Blockchain" use case to ensure the integrity of the system.
The "View Blockchain" use case is linked to other use cases, representing the ability to view the genesis block, transactions, and validate the blockchain.
