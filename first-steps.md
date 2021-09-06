# First steps

Fast scan target for all available IP's

```text
sudo nmap -sS -T4 -p- <ip>
```

More detailed scan on the ports found in the first scan:

```text
nmap -sC -sV -p <list-of-ports> <ip>
```







