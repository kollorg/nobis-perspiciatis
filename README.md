[![React Native Zephyr — Formidable, We build the modern web](https://raw.githubusercontent.com/FormidableLabs/@kollorg/nobis-perspiciatis/master/@kollorg/nobis-perspiciatis-Hero.png)](https://formidable.com/open-source/)

[![github][github-static-analysis-image]][github-url]
[![github][github-unit-test-image]][github-url]
[![npm][npm-image]][npm-url]
[![docs][docs-image]][docs-url]
[![Maintenance Status][maintenance-image]](#maintenance-status)

## Overview

React Native Zephyr is a [TailwindCSS](https://tailwindcss.com)-inspired styling library for React Native.

TailwindCSS is a brilliant library, but it's built for CSS and the web browser – and these are tools that are not available in React Native projects. This project aims to borrow some of the core ideas of TailwindCSS and implement them in the context of React Native applications.

React Native Zephyr, out of the box, provides:

- a thorough set of [built-in styling utilities](./docs/default-classes.md) (spacing, colors, typography, etc.);
- an [extendable and overridable theming system](./docs/extending-the-theme.md);
- **type-safety** for speedy and confident development;
- [dark-mode support](./docs/dark-mode.mdx) out of the box;
- [clsx-like syntax](./docs/dynamic-classname-list.md) for applying dynamic style classes.

Head over to [the docs](https://formidable.com/open-source/@kollorg/nobis-perspiciatis/) to learn more.

## Installation

In your React Native or Expo project, install `@kollorg/nobis-perspiciatis` using your favorite package registry tool such as npm, yarn, or pnpm.

```shell
npm install @kollorg/nobis-perspiciatis
```

```shell
yarn add @kollorg/nobis-perspiciatis
```

```shell
pnpm add @kollorg/nobis-perspiciatis
```

There is no further installation as @kollorg/nobis-perspiciatis is a pure JS library with no native dependencies. See our [Quick Start](https://formidable.com/open-source/@kollorg/nobis-perspiciatis/quick-start#step-2-wrap-your-app-in-a-styleprovider) guide to get started with configuration.

[github-unit-test-image]: https://github.com/kollorg/nobis-perspiciatis/workflows/Unit%20Test/badge.svg
[github-static-analysis-image]: https://github.com/kollorg/nobis-perspiciatis/workflows/Static%20Analysis/badge.svg
[github-url]: https://github.com/kollorg/nobis-perspiciatis/actions
[npm-image]: https://img.shields.io/npm/v/@kollorg/nobis-perspiciatis
[npm-url]: https://www.npmjs.com/package/@kollorg/nobis-perspiciatis
[docs-image]: https://img.shields.io/badge/docs-visit%20site-blue
[docs-url]: https://formidable.com/open-source/@kollorg/nobis-perspiciatis/
[maintenance-image]: https://img.shields.io/badge/maintenance-active-green.svg?color=brightgreen&style=flat
