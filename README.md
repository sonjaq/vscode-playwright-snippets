<h1 align="center">VS Code - 🎭 Playwright Playwright Snippets</h1>

## ℹ️️ Description

This Visual Studio Code extension adds predefined useful code snippets for 🎭 [Playwright](https://github.com/microsoft/playwright).

These were forked from [nitayneeman/vscode-puppeteer-snippets](https://github.com/nitayneeman/vscode-puppeteer-snippets) and are being adapted for Playwright.

<br>

## 👨🏻‍🏫 How to Use

The first thing you need to do is installing the [extension](https://marketplace.visualstudio.com/items?itemName=sonjaq.playwright-snippets).

Basically, there are two ways to apply the snippets:

### 1. Direct Typing

Start typing the prefix or just part of the snippet. Then, locate the snippets on the suggestions list and click on `TAB` or `ENTER`.

### 2. Command Palette

Open the Command Palette and type `Insert Snippet`. Then, simply choose the dedicated snippet.

<br>

## 📄 Snippets List

Below is attached a list of all supported snippets.

### Playwright

| Snippet             | Content                                    |
| ------------------- | ------------------------------------------ |
| `p-import`          | const playwright = require('puppeteer');   |
| `p-import-chromium` | const { chromium } = require('puppeteer'); |
| `p-import-firefox`  | const { firefox } = require('puppeteer');  |

### Browser

| Snippet                                   | Content                               |
| ----------------------------------------- | ------------------------------------- |
| `p-browser-browserContexts`               | browser.browserContexts               |
| `p-browser-close`                         | browser.close                         |
| `p-browser-createIncognitoBrowserContext` | browser.createIncognitoBrowserContext |
| `p-browser-disconnect`                    | browser.disconnect                    |
| `p-browser-newPage`                       | browser.newPage                       |
| `p-browser-waitForTarget`                 | browser.waitForTarget                 |
| `p-browser-on-disconnected`               | browser.on('disconnected',...)        |

### Page

| Snippet                         | Content                         |
| ------------------------------- | ------------------------------- |
| `p-page-$`                      | page.\$                         |
| `p-page-$$`                     | page.\\$\$                      |
| `p-page-$eval`                  | page.\$eval                     |
| `p-page-$$eval`                 | page.\$\$eval                   |
| `p-page-browser`                | page.browser                    |
| `p-page-click`                  | page.click                      |
| `p-page-close`                  | page.close                      |
| `p-page-content`                | page.content                    |
| `p-page-emulate`                | page.emulate                    |
| `p-page-emulateMediaFeatures`   | page.emulateMediaFeatures       |
| `p-page-emulateMediaType`       | page.emulateMediaType           |
| `p-page-emulateTimezone`        | page.emulateTimezone            |
| `p-page-focus`                  | page.focus                      |
| `p-page-goBack`                 | page.goBack                     |
| `p-page-goForward`              | page.goForward                  |
| `p-page-goto`                   | page.goto                       |
| `p-page-hover`                  | page.hover                      |
| `p-page-keyboard-down`          | page.keyboard.down              |
| `p-page-keyboard-press`         | page.keyboard.press             |
| `p-page-keyboard-sendCharacter` | page.keyboard.sendCharacter     |
| `p-page-keyboard-type`          | page.keyboard.type              |
| `p-page-keyboard-up`            | page.keyboard.up                |
| `p-page-metrics`                | page.metrics                    |
| `p-page-mouse-click`            | page.mouse.click                |
| `p-page-mouse-down`             | page.mouse.down                 |
| `p-page-mouse-move`             | page.mouse.move                 |
| `p-page-mouse-up`               | page.mouse.up                   |
| `p-page-pdf`                    | page.pdf                        |
| `p-page-reload`                 | page.reload                     |
| `p-page-screenshot`             | page.screenshot                 |
| `p-page-title`                  | page.title                      |
| `p-page-url`                    | page.url                        |
| `p-page-waitFor`                | page.waitFor                    |
| `p-page-waitForFunction`        | page.waitForFunction            |
| `p-page-waitForNavigation`      | page.waitForNavigation          |
| `p-page-waitForRequest`         | page.waitForRequest             |
| `p-page-waitForResponse`        | page.waitForResponse            |
| `p-page-waitForSelector`        | page.waitForSelector            |
| `p-page-waitForXPath`           | page.waitForXPath               |
| `p-page-waitForFileChooser`     | page.waitForFileChooser         |
| `p-page-on-close`               | page.on('close',...)            |
| `p-page-on-console`             | page.on('console',...)          |
| `p-page-on-dialog`              | page.on('dialog',...)           |
| `p-page-on-domcontentloaded`    | page.on('domcontentloaded',...) |
| `p-page-on-error`               | page.on('error',...)            |
| `p-page-on-frameattached`       | page.on('frameattached',...)    |
| `p-page-on-framedetached`       | page.on('framedetached',...)    |
| `p-page-on-framenavigated`      | page.on('framenavigated',...)   |
| `p-page-on-load`                | page.on('load',...)             |
| `p-page-on-metrics`             | page.on('metrics',...)          |
| `p-page-on-pageerror`           | page.on('pageerror',...)        |
| `p-page-on-popup`               | page.on('popup',...)            |
| `p-page-on-request`             | page.on('request',...)          |
| `p-page-on-requestfailed`       | page.on('requestfailed',...)    |
| `p-page-on-requestfinished`     | page.on('requestfinished',...)  |
| `p-page-on-response`            | page.on('response',...)         |
| `p-page-on-workercreated`       | page.on('workercreated',...)    |
| `p-page-on-workerdestroyed`     | page.on('workerdestroyed',...)  |

### General Examples

| Snippet                      | Content                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------- |
| `p-examples-basic`           | Creates a basic usage example of a page                                            |
| `p-examples-sleep`           | Creates an example that sleeps the browser with a specified time period            |
| `p-examples-dragAndDrop`     | Creates an example that drags the mouse from a point and drops it to another point |
| `p-examples-loadTimeMetrics` | Creates an example that evaluates `window.performance` within the page context     |

<br>

## 💁🏻 Contributing

This is an open source project. Any contribution would be greatly appreciated!
