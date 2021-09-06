# os

Get hostname

```text
hostname
```

System info

```text
uname -a //all
cat /proc/version
cat /etc/issue
```

Processor

```text
lscpu
```

Os details

```text
cat /etc/*-release
lsb_release -a
```

Active proccesses list

```text
ps aux
```

Installed packages

```text
// debian
dpkg -l

// centos/opensuse
rpm -qa
```

Kernel modules

```text
lsmod
```

Details on a kenel module

```text
 /sbin/modinfo <module>
```



