# Quasar App (quasar-webpack-electron-test)

Quasar/Webpack 3.11.1 > 3.11.2 build error Electron

https://stackblitz.com/edit/jf-quasar-webpack-electron3-11-2

## Working
```
package.json
  "@quasar/app-webpack": "3.11.1",
```
```
npm install
quasar dev -m electron \\ --> Working
quasar dev \\ --> Working
```

## Error Electron build
```
package.json
  "@quasar/app-webpack": "^3.11.2",
```
```
npm install
quasar dev -m electron \\--> Build error
quasar dev \\ --> Working
```

### Seems to have to do with modification:
https://github.com/quasarframework/quasar/commit/b4ce74000eecddd28cbaef956181ab5437e478be
