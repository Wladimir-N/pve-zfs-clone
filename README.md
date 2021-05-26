# pve-zfs-clone
Скрипт для клонирования LXC и KVM

Сделал интерактивный скрипт для создания клона который не занимает места на старте и создаётся очень быстро. Удалить клон и снимок на коснове которого он создавался можно потом прям с веб-интерфейса проксмокса.
https://t.me/ticketssettinru/187

# Установка через git:

1) Клонируем репозиторий

```bash
git clone git@github.com:Wladimir-N/pve-zfs-clone.git
```

2) Создаем ссылку на исполняемый файл в директории bin

```bash
chmod +x $(pwd)/pve-zfs-clone/pve-zfs-clone
ln -s $(pwd)/pve-zfs-clone/pve-zfs-clone /usr/bin/pve-zfs-clone
```

Для вызова утилиты необходимо выполнить `pve-zfs-clone` из любой папки.
