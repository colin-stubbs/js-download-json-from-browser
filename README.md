# js-download-from-browser

Download in-browser generated content as a file, no server component necessary

On load this page will create a simple JSON string from a JS object, it will create a blob of type application/json based on the string.

The link can then be used to trigger "download" of the file, which really just means copy/write from blob in memory to location specified by the user (or default download location if the browser is configured to simply download)

Using this you can avoid having to use a server side component to allow the user to download a file with content that has been generated in browser.
