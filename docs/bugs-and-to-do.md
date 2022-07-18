# Known Bugs and To-Do List

## Miscellaneous

* Whatever else that's missing...

## New (2021/12/31)

```javascript
ipcRenderer.on('action', (event, arg) => {
  switch (arg) {
    case 'exiting':
      if (EditingMode) {
        quit();
      }

      break;
    default:
      break;
  }
});

```
