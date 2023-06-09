# Hierarchical Categories of Astral Codex Ten Comments
Uses OpenAI text [embeddings](https://platform.openai.com/docs/guides/embeddings/what-are-embeddings) 
to construct a hierarchy of categories for comments on [Astral Codex Ten](https://astralcodexten.substack.com).

You can explore the structure of categories in the interactive demo at [matthagy.github.io/acx_comment_category_hierarchy](https://matthagy.github.io/acx_comment_category_hierarchy/)

![Screenshot](./img/screenshot.png "Screenshot")

Learn more about the methods in [Hierarchical categorization using OpenAI: Methods exposition](https://matthagy.substack.com/p/hierarchical-categorization-using)

You can build the webpage by running the following commands in this directory.
```bash
npm install
npx webpack --mode=development --devtool=eval-source-map
```

The site can then be viewed by opening `dist/index.html` in a browser.

Additionally, it can be deployed to a GitHub Pages site by running the following command.
Note you'll have to change the `repository.url` field in `package.json` to match your repository.

```bash
npm run deploy
```