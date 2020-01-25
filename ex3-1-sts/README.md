# StatefulSet

```bash
kubectl run mysql --image=mysql:5.7.29 -it --rm --restart=Never bash
```

```bash
mysql -h mysql-service -uroot -prootpassword -Dexample -e "SHOW DATABASES;"
```
