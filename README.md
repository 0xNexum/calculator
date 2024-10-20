# Patika.dev Web3 Operations and Analytics Missions

The dapp provides an interface that exposes the following methods:

**add**: accepts input and performs addition.

**sub**: accepts input and performs subtraction.

**mul**: accepts input and performs multiplication.

**div**: accepts input, performs division, and returns an optional type to guard against division by zero.

**clearall**: clears the cell variable by setting its value to zero.

## Prerequisites
This example requires an installation of:

[x] Install the [IC SDK](https://internetcomputer.org/docs/current/developer-docs/getting-started/install/).

[x] Clone the example dapp project: git clone https://github.com/0xNexum/calculator

Begin by opening a terminal window.

### Step 1: Navigate into the folder containing the project's files and start a local instance of the replica with the command:
cd examples/motoko/calc

dfx start --background
### Step 2: Deploy the canister with the command:
dfx deploy
### Step 3: Run a calculator function. For example, to multiply 2 by 3:
dfx canister call calc add '(2)'

dfx canister call calc mul '(3)'

Output:

(2 : int)

(6 : int)
