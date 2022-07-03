# VPN AutoScript by Techsolution11
```
rm -f setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/kelvintan1101/script/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
