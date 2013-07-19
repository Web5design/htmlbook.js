# htmlbook.js

Parses HTML into [HTMLBook](https://github.com/oreillymedia/htmlbook).

## Setup

### Browser

Add the htmlbook.js script to a page with jQuery (tested with jQuery 1.10.2) and [Marked](https://github.com/chjj/marked).

### Node.js

Install with npm: `npm install htmlbook`

## Usage

For both the browser and Node.js, usage is the same

```
var input = "HTML TEXT OR JQUERY OBJECT"
var output = HTMLBook(input).parse(opts);
```

### Opts

Below is a list of available options, default value is emphasized.

- sourceFormat: _html_ or markdown
- fragment: _false_ or true
- level: _chapter_ or book