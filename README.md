# X.com Dorker Tool

A sleek, single-page tool for crafting and saving advanced Twitter (X) search queries — perfect for bug bounty hunters and OSINT researchers. Quickly search by domain, subdomain, company name, or any keywords to uncover hidden gems for your targets.

## Features

- Enter custom dorks with `{{target}}` placeholder for dynamic searching
- Supports domains, subdomains, people, companies, and keywords
- Save, reuse, and manage your favorite dorks with localStorage
- Clear saved dorks anytime with a reset button
- Responsive, beautiful UI built with Tailwind CSS
- Opens search results in a new tab on X.com

## Usage

1. Enter your target (domain, subdomain, keywords, company name, etc.) in the input box.
2. Click any saved dork to perform the search on X.com.
3. Add new dorks to your saved list for quick access later.
4. Clear all saved dorks with the reset button if needed.

## Getting Started

Simply open the `index.html` file in any modern browser or host it via GitHub Pages.

## Example Dorks

- `site:{{target}} error.log`
- `from:{{target}} -filter:retweets lang:en`
- `site:{{target}} ".env" OR "credentials"`
- `"{{target}}" filetype:pdf confidential`

Replace `{{target}}` with your desired search target.

## Contributing

Feel free to submit issues or pull requests for improvements!

## License

MIT License © H4K2LIV3

---

Made with ❤️ by H4K2LIV3 | Hosted on GitHub Pages
