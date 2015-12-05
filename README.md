## build images

### build jessie-base image

```
packer build -var account_file=/path/to/credential.json --var project_id=your-proj-id jessie-base.json
```

### build sid-base image

```
packer build -var account_file=/path/to/credential.json --var project_id=your-proj-id sid-base.json
```

## TODO

 * replace ntp with systemd-timesyncd

