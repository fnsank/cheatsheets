### Get information about listening services, -P port, -M local TCP/UDP ports, -l login names, -n network numbers
```
lsof -Pnl +M -i4
lsof -Pnl +M -i6
```

### Geet information for specific port number
```
sudo lsof -i :33991
```

