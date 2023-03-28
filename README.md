# DisableUbuntuCloudInitScript
Script stops/disables cloud init from starting

## What it does

- Creates an empty file with the name `cloud-init.disabled`  in the `/etc/cloud/` to prevent the service from starting with the following command
```

sudo touch /etc/cloud/cloud-init.disabled

```
