# Export Note to HTML.workflow

This simply exports the selected Apple Note to HTML. 

## Filename

The filename is based on the ID of the note, e.g. `13216.html`.

## Images

Any embedded images will be base64 encoded into the `.html` file.

## metadata

Some metadata is embedded in the HTML file:

```html
<!--created_date:Wednesday, October 9, 2024 at 1:27:53 PM-->
<!--updated_date:Wednesday, October 9, 2024 at 3:21:15 PM-->
```

## Usage

Download the `.workflow` file (from Releases) to `~/Library/Services/Export Note to HTML.workflow` and find it in the Notes &gt; Services menu.

## Known Issues

- PDF documents to not show when exporting
