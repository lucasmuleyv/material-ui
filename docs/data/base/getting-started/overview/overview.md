# MUI Base - Overview

<p class="description">MUI Base is a library of headless ("unstyled") React UI components and low-level hooks.</p>

## Introduction

MUI Base is a library of unstyled React UI components.
These components were extracted from [Material UI](/material-ui/getting-started/overview/), and are now available as a standalone package.
They feature the same robust engineering but without implementing Material Design.

MUI Base includes prebuilt components with production-ready functionality, along with low-level hooks for transferring that functionality to other components.

With MUI Base, you can rapidly build on top of our foundational components using any styling solution you choose—no need to override any default style engine or theme.

:::info
**Note:** as of today, MUI Base is in alpha.

We're adding new components and features regularly, and you're welcome to contribute!

Look for the [`package: base`](https://github.com/mui/material-ui/labels/package%3A%20base) label on open issues and pull requests in the `mui/material-ui` repository on GitHub to see what other community members are working on, and feel free to submit your own.
:::

## Advantages of MUI Base

- **Ship faster:** MUI Base gives you the foundational building blocks you need to assemble a sleek and sophisticated user interface in a fraction of the time that it would take to do it all from scratch.
- **You own the CSS:** unlike Material UI, which uses Emotion as a default style engine, MUI Base has no built-in styling solution.
  This means you have complete control over your app's CSS.
- **Accessibility:** MUI Base components are built with accessibility in mind.
  We do our best to make all components screen reader-friendly, and offer suggestions for optimizing accessibility throughout our documentation.

## MUI Base vs. Material UI

MUI Base features many of the same components as [Material UI](/material-ui/getting-started/overview/), but without the Material Design implementation.

MUI Base is not packaged with any default theme or built-in style engine.
This makes it a great choice if you need complete control over how your app's CSS is implemented.

You could think of MUI Base as the "skeletal" or "headless" version of Material UI—in fact, future versions of Material UI (starting with v6) will use these components and hooks for their foundational structure.
