# Easy Apache 4 profile
Easy Apache 4 profile that can be install on any cPanel server. It will install PHP modules required by most web software including Symfony, Magento 1 and Magento 2.

# Installing this profile
```sh
wget -O /tmp/XigenEasyApache.json "https://raw.githubusercontent.com/XigenIO/cPanel-EA-4-Profiles/master/XigenEasyApache.json"
/usr/local/bin/ea_install_profile --install /tmp/XigenEasyApache.json
rm -rf /tmp/XigenEasyApache.json
```
