```
{
  "name": "ng2-getting-started",
  "version": "0.0.1",
  "dependencies": {
    "angular2": "2.0.0-alpha.35",
    "es6-module-loader": "^0.16",
    "systemjs": "^0.16",
    "traceur": "0.0.91"
  },
  "scripts": {
    "postinstall": "cd src && tsd reinstall -r -o && cd ..",
    "tsc": "tsc -p src -w",
    "start": "live-server --open=src"
  }
}

```