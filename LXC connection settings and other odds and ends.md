Чтобы разрешить SSH-доступ к LXC-контейнеру, войдите в него через консоль хоста 
---
```
pct enter 100
```
Установите SSH-сервер 
```
apt update && apt install openssh-server 
```
Откройте файл настройки: 
```
nano /etc/ssh/sshd_config.
```
Разрешите вход под root, если это нужно: найдите строчку PermitRootLogin и установите значение yes.

Чтобы tmdb.org открывался с ру ip, нужно в настройках adguard home, добавить строки в Upstream DNS-серверы
---
```
[/themoviedb.org/]9.9.9.10
[/tmdb.org/]9.9.9.10
[/image.tmdb.org/]9.9.9.10
```
