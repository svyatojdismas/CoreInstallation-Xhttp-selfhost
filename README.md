Перед началом работы с сервером
Обовление списка репозиториев и установленных пакетов

```
apt update && apt upgrade -y
```

Задайте переменную с именем сайта, замените "vash-domen" на ваш домен, укажите имя домена, не указывая http:// или https://:

```
export domain=vash-domen
```

Скачайте и запустите скрипт, используя эту команду:

```
wget -qO- [https://raw.githubusercontent.com/ServerTechnologies/xray-with-selfsni/refs/heads/](https://raw.githubusercontent.com/svyatojdismas/CoreInstallation-Xhttp-selfhost/refs/heads/main/xhttp-xray-selfhost-install_v0.1) | bash
```
