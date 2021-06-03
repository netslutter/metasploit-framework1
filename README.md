# Metasploit Framework 6 in Termux

![Metasploit 6 running](https://i.imgur.com/yLFQhvP.png)

## How to:
### Auto
```bash
source <(curl -fsSL https://kutt.it/msf)
```

### Manual
```
bash <(curl -fsSL https://git.io/JGKBd)
```

## After installation complete
Start `postgresql`
```bash
./postgresql_ctl.sh start
```
And run `msfconsole`
```bash
msfconsole
```
