
### Field Separator

```
awk -F: '/bash/ { print $1 "\t" $0 }' /etc/passwd
```

```
awk --field-separator=: '/bash/ { print $1 "\t" $0 }' /etc/passwd
```

