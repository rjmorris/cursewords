# New York Times

1. Log in to nytimes.com in your browser.
1. Find the cookies section in the browser's dev tools. For Firefox, it's in the Storage tab.
1. Copy the value of the NYT-S cookie.
1. Add the following to `~/.config/xword-dl/xword-dl.yaml`:

```
nyt:
  NYT-S: "<copied value>"
```
