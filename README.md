# Quick Overview
```
This Packer file is used as a method of enabling consistent deployment/provisioning of a base automation framework.

Currently, it's deploying Gitlab and Saltstack.

```

# To build
```
packer build -only=vmware-iso j-edi-base-packer.json
```

# Credentials
```
Username: juniper
Password: Juniper1
```