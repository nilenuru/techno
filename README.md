# Xiaomi AX3000T

**Полная настройка**
```sh
wget --no-check-certificate -O /tmp/universal_config.sh https://raw.githubusercontent.com/nilenuru/techno/refs/heads/master/universal_config.sh && chmod +x /tmp/universal_config.sh && /tmp/universal_config.sh

```
### Разблокировка сайтов с помощью youtubeUnblock + https-dns-proxy
Разблокировка сайтов с помощью подмены **Hello пакетов DPI** (приложение **youtubeUnblock**) + точечное перенаправление доменов, которые находятся в **геоблоке на ComssDNS** (через перенаправление dnsmasq и пакет **https-dns-proxy**) + добавление правил для **блокировки протокола QUIC** на уровне роутера

Для корректной работы скрипта нужны установленные пакеты **youtubeUnblock** и **https-dns-proxy**

**Установка**
```sh
wget -O - https://raw.githubusercontent.com/nilenuru/techno/refs/heads/master/universal_config.sh | sh

```
**Откат**
```sh
wget -O - https://raw.githubusercontent.com/nilenuru/techno/refs/heads/master/off_universal_config.sh | sh


```

### Разблокировка сайтов с помощью WARP от CloudFlare

**Установка**
```sh
https://raw.githubusercontent.com/nilenuru/techno/refs/heads/master/awg_config.sh && chmod +x /tmp/awg_config.sh && /tmp/awg_config.sh
```
**Откат**
```sh
wget -O - ttps://raw.githubusercontent.com/nilenuru/techno/refs/heads/master/off_awg_config.sh | sh
```
