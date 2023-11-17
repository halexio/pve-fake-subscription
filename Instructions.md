## Instructions
Host domain on private server `shop.maurer-it.com`

Install:
```shell
wget http://shop.maurer-it.com/pve-fake-subscription/pve-fake-subscription_0.0.7a_all.deb && dpkg -i pve-fake-subscription_*.deb && rm pve-fake-subscription_*.deb
```

Update:
```shell
apt purge pve-fake-subscription && wget http://shop.maurer-it.com/pve-fake-subscription/pve-fake-subscription_0.0.7a_all.deb && dpkg -i pve-fake-subscription_*.deb && rm pve-fake-subscription_*.deb
```

Remove:
```shell
apt purge pve-fake-subscription
```
(make sure `shop.maurer-it.com` is resolving to its real ip address)
