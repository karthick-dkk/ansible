### Print status of nginx (print 3 lines after macthed patter)

```
ansible all -i inventory  -a "systemctl status nginx" -u cartadmin  |  grep -i -E 'active|CHANGED' -A 3
```
