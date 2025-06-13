# Node Example

This example demonstrates how to use the SDK in a Node.js environment.

## Setup

1. Build the SDK
   ```bash
   cd packages/sdk
   pnpm build
   ```
2. Install dependencies
   ```bash
   cd apps/node
   pnpm install
   ```
3. Create a `.env` file and set `PRIVATE_KEY` with your account key.

## Running

```bash
pnpm run dev
```

### Examples

```bash
pnpm run dev moneymarket <user_address>
```

```bash
pnpm cosmos borrow <token> <amount>
```

```bash
pnpm cosmos supply <token> <amount>
```
