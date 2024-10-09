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

### Data

```
https://fuellabs.github.io/fuel-ecosystem/projects.json
```

### Images

```
https://fuellabs.github.io/fuel-ecosystem/assets/{project.image}.jpeg
```
