# Ubuntu Mate enable remote desktop

## Update 

```bash
sudo apt-get update
```

## Install XRDP

```bash
sudo apt-get install xrdp
```

## Open port on firewall

```bash
sudo ufw allow 3398
```

## Close port on firewall

```bash
sudo ufw deny 3398
```
