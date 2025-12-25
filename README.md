# Soul Inspiration

A repository for Soul Inspiration — motivational content and small business resources.

Getting started
- Edit `index.html` to update the homepage, or add files inside folders such as `assets/`.
- To add files using the web UI: click "Add file" → "Create new file" or "Upload files".

Quick start (local)
1. Clone the repo:
   ```
   git clone https://github.com/soulinspirationela-lab/soul-inspiration.git
   cd soul-inspiration
   ```
2. Edit files, then:
   ```
   git add .
   git commit -m "Update"
   git push
   ```

Using the shared stylesheet
- A basic stylesheet is available at `assets/css/styles.css`. You can link it from HTML files like:
  ```html
  <link rel="stylesheet" href="/assets/css/styles.css">
  ```
  (When previewing locally or via GitHub Pages, using an absolute path from the repo root works well; relative paths also work.)

Examples
- An example page lives at `examples/sample.html` and demonstrates linking the stylesheet and a simple layout.
- Example content (Markdown) is available at `examples/sample.md` as a quick template for pages/posts.

Contributing
- Fork or create a branch for changes.
- Open issues to suggest content or improvements.
- When you add pages, put reusable assets in `assets/` and example content in `examples/`.

License
This project is released under the MIT License — see LICENSE file.
