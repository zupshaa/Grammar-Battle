# Grammar Battle

A Jeopardy-style grammar game board for classroom use. Static site: HTML, CSS and JavaScript in one file, no build step, no backend.

## Publish on GitHub Pages

1. Sign in at github.com and click **New repository**. Name it (for example `grammar-battle`), set it to **Public**, and click **Create repository**.
2. Click **uploading an existing file**, drag in `index.html` (and this README if you like), then click **Commit changes**.
3. Open the repository's **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Choose branch **main** and folder **/ (root)**, then click **Save**.
5. Wait 1 to 2 minutes and refresh the Pages screen. Your site appears at `https://YOUR-USERNAME.github.io/grammar-battle/`.

Note: the file must be named `index.html` and sit in the repository root.

## Edit the questions

Open `index.html` and find the block marked `QUESTION BANK`. Each category has 5 items in order ($5, $10, $20, $50, $100), each with `q` (question) and `a` (answer).
- `\n` makes a line break.
- `**text**` underlines and bolds the text.
- Commit the change on GitHub and the site updates within a minute or two.

## Notes
- Tile "used" fading lasts until the page is refreshed.
- Fonts load from Google Fonts. If the classroom is offline, the page falls back to the system font.
