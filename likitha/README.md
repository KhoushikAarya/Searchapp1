# Cosmos DB User Query Script

This Python script connects to **Azure Cosmos DB** to retrieve user information and their latest promoted queries using the Azure SDK.

## 📌 Features

- Connects to Cosmos DB using environment variables
- Queries the **users** container by first and last name
- Retrieves the latest 3 promoted queries associated with a user
- Uses `azure-cosmos` SDK and `dotenv` for secure credential handling

## 🛠️ Requirements

- Python 3.7+
- Azure Cosmos DB account
- Environment variables set in a `.env` file

### Python Packages

Install required packages:

```bash
pip install azure-cosmos python-dotenv
