# Flow Cadence Fruits Contract
This project contains a smart contract implemented in Flow Cadence which defines a dictionary that maps fruit names to fruit structures. The contract allows adding new fruits to the dictionary and retrieving fruits by name.

# Code :
The project contains three files: contract, transaction, and script.

# Contract :
The Contract file defines the smart contract. It contains a public dictionary Fruits which maps from String to Fruit structures. The Fruit structure has three fields: Name, Quantity, and Taste. The contract provides a public function addFruitFn which takes three parameters Name, Quantity, and Taste and adds a new Fruit structure to the Fruits dictionary with the given values.

# Transaction :
The Transaction file defines a transaction transaction which takes three parameters Name, Quantity, and Taste and calls the addFruitFn function to add a new Fruit structure to the Fruits dictionary.

# Script :
The project also contains a script file FruitsScript.cdc which defines a public function main that takes a Name parameter and returns the Fruit structure with the given name from the Fruits dictionary.

# Usage :
To use the contract, deploy it to a Flow blockchain network and interact with it using a Flow client. Use the Transaction file to create a new transaction and add a new fruit to the Fruits dictionary. Use the Script file to retrieve a fruit by name from the Fruits dictionary.
