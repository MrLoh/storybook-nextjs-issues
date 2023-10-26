# Demonstration of issues with Next.js 13.5 and Storybook 7.5

steps to reproduce error:
- `npm install`
- `npm run storybook`

you should get something along the lines of:
```
Module parse failed: Unexpected token (3:2128)
You may need an appropriate loader to handle this file type, currently no loaders are configured to process this file. See https://webpack.js.org/concepts#loaders
| import { __commonJS } from './chunk-JRLSWQMA.mjs';
| 
> var require_markdown=__commonJS({"../../node_modules/refractor/lang/markdown.js"(exports,module)```