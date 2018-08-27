---
description: selinux quick reference guide - RHEL/CentOS 7
---

# selinux

Checking selinux current mode:

```bash
# will only display just the mode
getenforce
# for additional information including se policy 
sestatus            
```

Configuration file for selinux is located at /etc/selinux/config 



```text
ls -Z
```

```text
getsebool -a
```

```text
semanage fcontext --list
```



Using selinux's permissive mode allows selinux to log events to /var/log/messages

```text
grep "selinux" /var/log/messages
```





