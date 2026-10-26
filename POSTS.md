# Posts

Add Markdown files to `src/content/posts/`. Copy `example.md` to get started.

Each file has a title, description, author, date, type (`blog` or `newsletter`), image, imageAlt, and tags. Images in `public/images/` use `/images/filename.jpg` paths.

The filename determines the URL: `example.md` → `/posts/example/`.

- `src/content.config.ts`: shared metadata schema.
- `src/layouts/PostsLayout.astro`: basic page shell and formatting.
- `src/pages/posts/[...id].astro`: shared article template.
- `src/pages/posts/index.astro`: minimal listing using `getCollection("posts")`, newest first.

Run `bun run build` to generate the pages. New content requires rebuilding and deploying.
