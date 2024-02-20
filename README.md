[![Coverage Status](https://coveralls.io/repos/github/magento/pwa-studio/badge.svg?branch=develop)](https://coveralls.io/github/magento/pwa-studio?branch=develop)

# PWA Studio

Magento PWA Studio is a collection of tools that lets developers build complex Progressive Web Applications on top of Magento 2 stores.

## Contributions

Are you interested in contributing to the PWA Studio project?
Check out the [community wiki][] to learn how to contribute to PWA Studio.

If you are looking for an issue to work on, visit our [community backlog board][] and look at the **Ready for Development** column.

For more information about contributing to this repository, see the [Contribution guide][].

## Useful links

[PWA Studio documentation site][documentation site] -
The best place to start learning about the tools and the technologies that PWA Studio provides.
Here, you can learn PWA Studio concepts, find API reference docs, and read tutorials on how to use PWA Studio to create your own PWA storefront.

Here are some popular topics to help you get started:

- [PWA Studio Overview][] - A high level overview of PWA Studio and what it provides to developers
- [PWA Studio Beginner Guide](https://www.youtube.com/watch?v=n8C87KQT-Bg)
- [Tools and libraries][] - A list of tools and libraries developers need to be familiar with to use PWA Studio
- [PWA Studio fundamentals][] - A series of tutorials covering common storefront development tasks
- [PWA Studio best Practices](https://developer.adobe.com/commerce/pwa-studio/guides/best-practices/)


### Venia

[![Venia](https://raw.githubusercontent.com/wiki/magento/pwa-studio/images/venia.png)][venia]

[Venia][] is a Magento PWA storefront created and powered by PWA Studio tools and libraries.
Developers can use Venia as a reference storefront for their own projects or as a starting point for customization.

## About this repository

To facilitate local development, testing, and versioning, PWA Studio is structured as a monorepo using [Yarn Workspaces][].
Packages in this repository are independently published to [NPM][].
Install individual packages as needed instead of installing the entire `pwa-studio` project as a dependency of your project.

**Note:** If you are installing the whole PWA Studio monorepo, please be aware that the project uses `yarn workspaces` and does not support `npm install`. Please use `yarn install` instead.

### Packages

This repository includes the following packages:

- [**peregrine**](https://developer.adobe.com/commerce/pwa-studio/guides/packages/peregrine/) - A component library for adding logic to visual components
- **venia-ui** - A library of visual components for PWA storefront projects
- **venia-concept** - A concept storefront project built using PWA Studio tools
- [**pwa-buildpack**](https://developer.adobe.com/commerce/pwa-studio/guides/packages/buildpack/) - A tooling library to help with PWA storefront development
- [**upward-spec**](https://developer.adobe.com/commerce/pwa-studio/guides/packages/upward/) - UPWARD specification and test suite
- [**upward-js**](https://developer.adobe.com/commerce/pwa-studio/guides/packages/upward/javascript/) - A reference implementation of the UPWARD specification
- **babel-preset-peregrine** - A [babel][] preset plugin that is required to use peregrine components
- **graphql-cli-validate-magento-pwa-queries** - A script to validate your project's GraphQL queries against a schema
- [**pwa-devdocs**](pwa-devdocs) - Project source for the [documentation site][]

If you have an issue that cannot be resolved, please [create an issue][].

### PWA Studio UI Kit for Adobe XD

Adobe XD makes handoff between designers and engineers more efficient through easy-to-use collaboration tools. The [PWA Studio UI Kit][] contains a collection of templates and components compatible with Adobe Commerce.

# pwa-app

troubleshooting:
error:
0308010C:digital envelope routines::unsupported

need to add environment node variable to sistem
 run the below code

export NODE_OPTIONS=--openssl-legacy-provider
