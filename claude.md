# API Documentation Rules

## Read-Only Areas
- The `crypto_hooks` directory is read-only and must never be modified.

## API Structure
- APIs are grouped by:
  - ENS
  - ERC20
  - ERC721
  - Pricing
  - Gas
  - Prices
- Both GET and POST requests are used.

## Documentation Output
- When generating documentation, produce OpenAPI 3.0–compatible YAML
- Output must be suitable for Swagger UI
- Do not generate code or modify existing files
- For each of the endpoints, read docs online and figure out the correct response object