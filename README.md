# experiment-sqlite3-wasm
Description: Experiments and learning about sqlite3's WASM support.

I downloaded the zip file from the sqlite3 download page `https://sqlite.org/download.html`. At this time, the version was https://sqlite.org/2022/sqlite-wasm-3400000.zip.

I unzipped and moved to this repo as `sqlite-wasm`.

## First test

Installed a server tool to test things locally. I choose the one below and installed with:
```
$ go install -v github.com/projectdiscovery/simplehttpserver/cmd/simplehttpserver@latest
```

After installing, I ran the demo like this:
```
# start the server in the sqlite-wasm folder
simplehttpserver -listen localhost:8000
```
Then I pointed by browser to `localhost:8000/demo-123.html`. It worked fine.

