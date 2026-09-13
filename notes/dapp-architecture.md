# dApp Architecture

A decentralized application (dApp) usually connects a user interface with blockchain-based services.

## Main Components

- **Frontend** — Provides the user interface.
- **Wallet** — Allows users to connect their account and approve transactions.
- **RPC Provider** — Handles communication between the application and the Base network.
- **Smart Contracts** — Execute application logic onchain.
- **Onchain Data** — Provides transaction and contract activity for the application.

## Basic Flow

A user interacts with the frontend, connects a wallet, and sends requests through the application. Read operations can retrieve blockchain data, while write operations may require the user to approve a transaction.

Keeping these components separated can make a dApp easier to develop, test, and maintain.
## Data Flow

A dApp can handle different types of blockchain interactions.

- Read requests retrieve public onchain data.
- Write requests create transactions that require wallet approval.
- RPC providers connect the application to the network.
- Smart contracts process onchain application logic.

Separating read and write operations can make application behavior easier to understand and maintain.
