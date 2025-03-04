# Introduction

WXT is a free and open source framework for building web extensions in an conventional, intuative, and safe way **_for all browsers_**.

WXT comes with full TypeScript support and auto-imports. Sounds familiar? That's right, **_WXT was based off of Nuxt_** and aims to provide the same greate DX and features.

![Example build output](../assets/cli-output.png)

## Conventions

WXT is an optionated framework. This helps keep projects consistent and easy to pick up.

- **Generated manifest**: Based on your project's file structure
- **Entrypoint configuration**: Configure entrypoints from the same file they're declare in
- **Type-safety is a priority**: Out-of-the-box TypeScript support with improved browser API typing
- **Simple output file structure**: Ouptut file paths minimize the path at runtime

## Development

WXT's dev server supports modern features like HMR to provide a lighting fast dev mode.

When changes can't be hot-reloaded, like content scripts or background scripts, they're reloaded individually to prevent reloading the entire extension and slowing down your development cycle.

## Production-ready

Production builds are optimized for store review, changing as few files as possible between builds.

In addition, WXT fully supports Firefox's source code requirements when using a bundler. It will automatically create and upload a ZIP file of your source code.

:::info
See [Publishing](./publishing.md) for more info around production builds.
:::
