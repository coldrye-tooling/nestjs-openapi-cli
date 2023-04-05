# nest-swagger-cli


## Usage

### Install Locally

NOTE: ATM this has not been published to npmjs.com, so you will have to clone the repo and install it locally

To install, just run

```
cd nest-swagger-cli
pnpm install
pnpm build
npm link
```

and to uninstall, use

```
npm uninstall -g nest-swagger-cli
```

### Generate an OpenAPI Document From a Local Package

NOTE: ATM you have to transpile your package first before use

```
nest-swagger package -p $PWD/path-to-package -m dist/app.module
```
