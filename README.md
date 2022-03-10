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

### React

``` ts
import { md } from "awesome-md-renderer";

const mdStr = `
# Title

__bold__
`;

export const MD: React.FC = () => <div dangerouslySetInnerHTML={{ __html: md(text) }} />;
```

## Prism styles

Any default or custom theme styles can be generated on the [Prism package main page](https://prismjs.com/download.html#themes=prism&languages=markup+css+clike+javascript).

