# 🥞 Toll UIkit

[![Version](https://img.shields.io/npm/v/@fortuneswapfinance/uikit)](https://www.npmjs.com/package/@fortuneswapfinance/uikit) [![Size](https://img.shields.io/bundlephobia/min/@fortuneswapfinance/uikit)](https://www.npmjs.com/package/@fortuneswapfinance/uikit)

Toll UIkit is a set of React components and hooks used to build pages on Toll's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @fortuneswapfinance/uikit`

## Setup

### Theme

Before using Toll UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@fortuneswapfinance/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@fortuneswapfinance/uikit'
...
<ResetCSS />
```
