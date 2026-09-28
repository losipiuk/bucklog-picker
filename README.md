# bucklog-picker

Static Google Picker page used by the Bucklog app to let a user choose the family
spreadsheet (grants the app `drive.file` access to it). Served by GitHub Pages at
https://losipiuk.github.io/bucklog-picker/.

Contains no secrets: the OAuth token and config are passed by the app in the URL
fragment, which is never sent to the server.
