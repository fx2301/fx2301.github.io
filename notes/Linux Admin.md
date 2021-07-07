---
title: Linux Admin
created: '2021-07-02T08:46:55.638Z'
modified: '2021-07-02T14:09:14.017Z'
---

# Linux Admin

## Start a service on boot

```
systemctl enable --now snapd.service
```

## Clipboard copy / paste

```
echo "FOO" | xclip -selection clipboard
```

```
xclip -selection clipboard -o
```
