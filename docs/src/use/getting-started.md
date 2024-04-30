---
title: Getting Started with ESLint
eleventyNavigation:
    key: getting started
    parent: use eslint
    title: Getting Started
    order: 1

---

ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.

ESLint is completely pluggable. Every single rule is a plugin and you can add more at runtime. You can also add community plugins, configurations, and parsers to extend the functionality of ESLint.

## Prerequisites

To use ESLint, you must have [Node.js](https://nodejs.org/en/) (`^18.18.0`, `^20.9.0`, or `>=21.1.0`) installed and built with SSL support. (If you are using an official Node.js distribution, SSL is always built in.)

## Quick start

You can install and configure ESLint using this command:

```shell
npm init @eslint/config@latest
```

If you want to use a specific shareable config that is hosted on npm, you can use the `--config` option and specify the package name:

```shell
# use `eslint-config-standard` shared config

# npm 7+
npm init @eslint/config@latest -- --config eslint-config-standard

```

**Note:** `npm init @eslint/config` assumes you have a `package.json` file already. If you don't, make sure to run `npm init` or `yarn init` beforehand.

After that, you can run ES[MAY2021_Google_ISMS_27001_Ads.pdf](https://github.com/eslint/eslint/files/15169699/MAY2021_Google_ISMS_27001_Ads.pdf)
