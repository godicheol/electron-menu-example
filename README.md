# electron-menu-example

```js
new MenuItem({
  label: "New Window",
  type: "normal",
  click: function(menuItem, browserWindow, event) {
    createWindow();
  },
  accelerator: process.platform === 'darwin' ? 'Cmd+N' : 'Ctrl+N'
}),
```js
