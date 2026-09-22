## Fuel Ecosystem

The home for ecosystem applications building on the Fuel Network. Find all the relevant information like name, websites, logos and more.

## How to add a project

1. Fork this repository
2. Add your project to the end of the [projects.json](./projects.json) file.
3. Add an image to the [images](./images) folder with `.jpeg` extension.
3. Create a pull request to this repository.

## Schema

| Field | Description |
| --- | --- |
| `isLive` | Whether the project is live or not |
| `isFeatured` | Whether the project is featured or not |
| `contracts` | Contract information related to the project |
| `contracts[].abi` | URL of the contract's JSON ABI. The explorer uses it to decode calls and logs |
| `contracts[].market` | For order book contracts: `symbol`, `baseAssetId` and `quoteAssetId`, used to format amounts and prices |
| `callerContracts` | ABIs for contracts that have no fixed id, keyed by network. The explorer applies them to any contract that calls one of the project's `contracts` in the same transaction |
| `name` | The name of the project |
| `url` | The URL of the project |
| `tags` | The tags of the project |
| `description` | The description of the project |
| `github` | The URL of the GitHub repository |
| `twitter` | The URL of the Twitter account |
| `discord` | The URL of the Discord server |
| `image` | The name of the image file in the `images` folder |

## Images

All images should be in the `images` folder with extension `.jpeg`.

## How to use


### Local development

1. Install dependencies

```bash
pnpm install
```

2. Run `dev` script

```bash
pnpm dev
```

3. Open http://localhost:4000/projects.json

### Data

```
https://fuellabs.github.io/fuel-ecosystem/projects.json
```

### Images

```
https://fuellabs.github.io/fuel-ecosystem/assets/{project.image}.jpeg
```
