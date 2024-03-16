# Verdaccio

> 📦 Bit Ocean private npm registry.

## Deployment

Clone this repo and run via `docker-compose`:

```bash
docker-compose up -d
```

## Usage

### Add user account

npm adduser --registry https://npm.bit-ocean.studio

### Install packages

Add following to `.npmrc`:

```properties
@bit-ocean:registry=https://npm.bit-ocean.studio
```

### Revoke packages

If you want to revoke a package, you can use the following command:

```bash
npm unpublish -f [package-name]@[version]
```
