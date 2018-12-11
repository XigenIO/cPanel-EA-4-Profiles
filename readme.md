# Easy Apache 4 profile

This repo contains a custom Easy Apache 4 profile that can be install on any cpanel server. It installs PHP modules required by most web software. Supports Symfony, Magento1 and Magento2.


# Installing profile
```sh
wget -O /tmp/XigenEasyApache.json "https://git.xigen.co.uk/xigen/cpanel-ea-profiles/raw/master/XigenEasyApache.json"
/usr/local/bin/ea_install_profile --install /tmp/XigenEasyApache.json
rm -rf /tmp/XigenEasyApache.json
```
