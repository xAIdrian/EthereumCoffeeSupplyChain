### PROJECT SPECIFICATION
# Architect a Blockchain Supply Chain Solution - Part B

### Write Up

<table>
<tr><td>Project write-up - UML
</td><td>Project write-up include the following UML diagrams:

- Activity
- Sequence
- State
- Classes (Data Model)
</td></tr>
<tr><td>Project write-up - Libraries
</td><td>If libraries are used, the project write-up discusses why these libraries were adopted.
</td></tr>
<tr><td>Project write-up - IPFS
</td><td>If IPFS is used, the project write-up discusses how IPFS is used in this project.
</td></tr>
<tr><td>General Write Up
</td><td>A general write up exists to items like steps and contracts address.
</td></tr>
</table>

### Write smart contracts with functions

<table>
<tr><td>SupplyChain.sol contains required tracking functions.
</td><td>Smart contract implements functions to track.

For example:

- Product ID
- Product UPC
- Origination Information
- Farm
- Misc organization info
- Longitude & Latitude of geo coordinates
- Product notes

<tr><td>Ownable.sol contains required functions that establish owner and the transfer of ownership.
</td><td>Ownable.sol has required functions that establish owner and the transfer of ownership.

<tr><td>ConsumerRole.sol contains required functions that manage the consumer role.
</td><td>ConsumerRole.sol has required functions that manage the consumer role.

<tr><td>RetailerRole.sol contains required functions that manage the consumer role.
</td><td>RetailerRole.sol has required functions that manage the consumer role.

<tr><td>DistributorRole.sol contains required functions that manage the consumer role.
</td><td>DistributorRole.sol has required functions that manage the consumer role.

<tr><td>Additional roles implemented are integrated correctly.
</td><td>Student has implemented additional roles correctly.
</table>

### Test smart contract code coverage

<table>
<tr><td>Test smart contract tests all required functions.
</td><td>Project contains tests for the boiler plate functions and all tests are approved without error.
</table>

## Deploy smart contract on a public test network (Rinkeby)

<table>
<tr><td>Deploy smart contract on a public test network.
</td><td>Smart contract is deployed on on the Ethereum RINKEBY test network.

<tr><td>Project submission includes transaction ID and contract address
</td><td>Project submission includes a document (.md, .txt) that includes:

- Transaction ID
- Contract address
-- Hint: You can view Transaction ID and Contract ID from a blockchain explorer (e.g. Etherscan). Example Contract ID: https://rinkeby.etherscan.io/address/0xfb0720c0715e68f80c0c0437c9c491abfed9e7ab#code
</table>

### Modify client code to interact with a smart contract

<table>
<tr><td>Client code interacts with smart contract.
</td><td>Front-end is configured to:

- Submit a product for shipment (farmer to the distributor, distributor to retailer, etc).
- Receive product from shipment.
- Validate the authenticity of the product.
</table>

### Suggestions to Make Your Project Stand Out!
Optional: Implement Infura to store product image

- Ex: Farmer harvests coffee and upload pics w/ UPC hash
- Potentially only 2 methods needed upload() and read()
