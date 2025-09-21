# CopyClean Firefox Extension Settings

Default Settings for a Firefox WebExtension that extracts clean article content from web pages and copies it to the clipboard.

## Configuration

### Global Settings
- **Copy as Markdown**: Toggle between plain text and Markdown output

### Domain-Specific Selectors
Configure custom CSS selectors for specific websites:
- Domain: `nytimes.com`, Selectors: `article, .StoryBody`
- Domain: `medium.com`, Selectors: `article, .meteredContent`
- Domain: `wikipedia.org`, Selectors: `#mw-content-text, .mw-parser-output`
