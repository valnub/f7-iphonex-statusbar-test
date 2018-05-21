# install

```
npm install
```

# run

```
npm run cordova-run-ios
```

## Reproduce bug

Run in iPhone X simulator (using iOS 11.3) then rotate device to the left (landscape) and then rotate back to portrait. Status bar is gone. `<html>` element looses class `with-statusbar`. Problem is only visible if Safari devtools are **not connected** to simulator. If devtools are connected everything works fine.

## Screenshot

<img src="https://raw.githubusercontent.com/valnub/f7-iphonex-statusbar-test/master/x-status.jpg">
