# Awesome Markdown Renderer

Markdown renderer with GFM, Emoji, Katex, Prism and etc. support out of the box.


## Install

> npm i -S awesome-md-renderer

## Usage

``` ts
import { md } from "awesome-md-renderer";

const mdStr = `
# Title

__bold__
`;

const htmlStr = md(mdStr);
```
