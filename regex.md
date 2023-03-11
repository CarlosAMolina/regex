## Terminal

### Get /etc/hosts configured IP addresses

```bash
grep -oE "^([0-255].){3}[0-255]\s" /etc/hosts | sort -u
```

