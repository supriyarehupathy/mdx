import { Border, Blockquote, BlockLink } from 'rebass'

# MDX

MDX enables you to seamlessly use JSX in your Markdown documents.
This makes writing long-form content with components a blast.

__:heart: Powerful__: MDX makes it effortless to import and render components in your React/JSX-based projects.

__:computer: Component-based__: Use existing JSX components inside your MDX, and import MDX files as plain components.

__:fire: Blazingly blazing fast__: MDX has no runtime, all compilation occurs during the build stage.

> “It's extremely useful for using design system components to render markdown
and weaving interactive components in with existing markdown.”
>
> — [@chrisbiscardi](https://twitter.com/chrisbiscardi/status/1022304288326864896)

## Why?

Before MDX, some of the benefits of writing Markdown were lost when integrating with JSX.
Implementations were often template string-based which required lots of escaping and cumbersome syntax.

MDX seeks to make writing with Markdown _and_ JSX simpler while being more expressive.
The possibilities are endless when you combine components (that can even be dynamic or load data) with the simplicity of Markdown for long-form content.

## Features

- Fast
- No runtime compilation
- [Pluggable][remark-plugins]
- Element to React component mapping
- React component `import`/`export`
- Customizable layouts
- Webpack loader
- Parcel plugin
- Next.js plugin
- Gatsby plugin

## Try it

```.mdx
# Hello, world!

Here's an example of the [Rebass][] Donut rendered inside an MDX document.

<Donut value={2/3} />

[Rebass]: https://jxnblk.com/rebass
```

[md]: http://commonmark.org/
[jsx]: https://facebook.github.io/jsx/
[remark-plugins]: https://github.com/remarkjs/remark/blob/master/doc/plugins.md