# STM32F429xx spi exchange
## Clone project

Project use submodule from "Navigator" gittea. You must to connect to their VPN.

```bash
# wg0 - name of config file in /etc/wireguard/
sudo wg-quick up wg0
```

Now you can clone the project

```bash
git clone git@github.com:mm-milovanov/stm32-spi-exchange.git
cd ./stm32f429-to-sx1279
git submodule init
git submodule update
```

After end of work with repository exit close VPN connection

```bash
sudo wg-quick down wg0
```
