# DollMaker / Dress up game GUI

This is the GUI repository of my [DollMaker JS application](https://github.com/wolfderechter/DollMaker).

## Note

Currently only the `wails dev` build works because Wails can't access images not explicitly imported :(

I'll fix this in the future, hopefully.

## About

You can configure the project by editing `wails.json`.


## Live Development

To run in live development mode, run `wails dev` in the project directory. This will run a Vite development
server that will provide very fast hot reload of your frontend changes. If you want to develop in a browser
and have access to your Go methods, there is also a dev server that runs on http://localhost:34115. Connect
to this in your browser, and you can call your Go code from devtools.


## Building

To build a redistributable, production mode package, use `wails build`.
