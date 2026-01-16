# Yuki's Yarn

A simple Jekyll blog.

## Setup

1. Install Ruby (if not already installed)
2. Install dependencies:
   ```bash
   bundle install
   ```

## Running Locally

```bash
bundle exec jekyll serve
```

Then open http://localhost:4000 in your browser.

## Adding a New Post

1. Create a new file in the `_posts` folder
2. Name it: `YYYY-MM-DD-your-post-title.md`
3. Add frontmatter at the top:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD
   ---
   ```
4. Write your content in Markdown below the frontmatter

Posts are automatically listed on the homepage in reverse chronological order (newest first).

## Building for Production

```bash
bundle exec jekyll build
```

The static site will be generated in the `_site` folder.

