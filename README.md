# firewalld-services
Repository for firewalld service definitions

Add the service a service defintion as follows:

```
sudo firewall-cmd --permanent --new-service-from-file=<filename> --name=<servicename>
```

then enable it as follows:

```
firewall-cmd --permanent --add-service <servicename> 
```