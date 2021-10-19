Setting up the Plaid API without Docker

```
git clone https://github.com/plaid/quickstart.git

cd quickstart/node

# Copy the .env.example file to .env, then fill

# out PLAID_CLIENT_ID and PLAID_SECRET in .env
cp .env.example .env

# Install dependencies
npm install

# Start the backend app
./start.sh
```