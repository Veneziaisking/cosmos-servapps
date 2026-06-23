# Cosmos ServApps Marketplace

A custom community marketplace for Cosmos ServApps.

This repository provides a collection of ServApps for Cosmos, allowing users to easily install and manage applications directly from their Cosmos instance.

## Features

* Custom ServApps for Cosmos
* GitHub Pages integration
* Automatic marketplace deployment using GitHub Actions
* Custom icons and metadata support
* Easy installation directly inside Cosmos

## Marketplace URL

Add the following URL to your Cosmos marketplace sources:

```text
https://veneziaisking.github.io/cosmos-servapps/servapps.json
```

## Installation

1. Open your Cosmos dashboard.
2. Navigate to **Settings → Marketplace Sources**.
3. Add the marketplace URL above.
4. Save the configuration.
5. Your applications will now appear in the Cosmos marketplace.

## Repository Structure

```text
servapps/
├── app1/
│   ├── cosmos-compose.json
│   └── icon.png
├── app2/
│   ├── docker-compose.yml
│   └── icon.png
```

Each application folder can contain:

* `cosmos-compose.json`
* `docker-compose.yml`
* `icon.png`
* Additional metadata files

## GitHub Pages

This repository uses GitHub Pages to host the marketplace files.

Make sure GitHub Pages is enabled in the repository settings and configured to publish from the `gh-pages` branch or GitHub Actions.

## Contributing

Contributions, improvements, and new ServApps are welcome.

Please open an issue or submit a pull request.

## License

This project is provided as-is for the Cosmos community.
