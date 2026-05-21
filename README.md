# Ubuntu-proxy
```

ssh -R 10808:127.0.0.1:10808 root@IPIRAN
curl -I --proxy http://127.0.0.1:10808 https://www.google.com
sudo http_proxy=http://127.0.0.1:10808 apt update

curl -x http://127.0.0.1:10808 -sL https://raw.githubusercontent.com/smite-node.sh

sudo http_proxy=http://127.0.0.1:10808 https_proxy=http://127.0.0.1:10808 bash install-node.

export http_proxy=http://127.0.0.1:10808
export https_proxy=http://127.0.0.1:10808
env | grep -i proxy

```
