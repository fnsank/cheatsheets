### Check domain result
```
dig <domain> +short
```

### Reverse search (rDNS)
```
dig -x <ip> +short
```

### Get mail server
```
dig <domain> mx
```

### Zonetransfer on specific host
```
dig axfr @<dns-ip> <domain>
```

### Get any information
```
dig ANY @<dns-ip> <domain>
```

### Check sender policy framework
```
dig -t txt <domain> | grep -i spf
```

### Check txt records for third party software
```
dig -t txt <domain>
```

