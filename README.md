# LeetCode Toolkit

A userscript to enhance the LeetCode problem-solving experience by providing quick utilities on problem pages.

## Features

- Find & save official editorials for offline use
- Copy problem statements and descriptions as Markdown
- Download problems as Jupyter Notebooks
- Automatic code formatting on save
- Unlock IntelliSense in the LeetCode code editor

## Installation

1. Install a userscript manager:
   - [Tampermonkey](https://www.tampermonkey.net/)
   - [Greasemonkey](https://www.greasespot.net/)

2. Add the script to your manager:
   - **Option A**: Visit the raw script URL and click "Install":
     ```
     https://update.greasyfork.org/scripts/532158/LeetCode%20Toolkit.user.js
     ```
   - **Option B**: Copy the contents of `script.js` into a new script in your userscript manager.

3. Reload any LeetCode problem page to activate the toolkit.

## Usage

On any LeetCode problem page, use the newly added toolbar to:

- Save or view editorials
- Copy problem details as Markdown
- Download a ready-to-run Jupyter Notebook
- Format code automatically on save
- Enable IntelliSense in the online editor

## Development

1. Clone this repository:
   ```bash
   git clone <repo-url>
   ```
2. Open and modify `script.js` to customize features.
3. Reload the script in your userscript manager to test changes.

## License

Distributed under the MIT License.
