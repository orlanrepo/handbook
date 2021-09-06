# users

View home folders:

```text
ls -all /home
```

View passwd:

```text
cat /etc/passwd
cat /etc/passwd || grep -vE "nologin|false" /etc/passwd
cat /etc/passwd | cut -d: -f1
```

Get shadow file passwords

```text
cat /etc/shadow
```

Get available groups

```text
cat /etc/group
```

Check passwd permissions

```text
ls -lah /etc/passwd
```



