# wireguard_install
Установщик WireGuard (черновик)
Требуется сервер с KVM-виртуализацией и наличием канала минимум 100 Мбит/с и желательно с безлимитным трафиком.
Будем использовать Ubuntu 22.04.2 LTS, подключаемся через консоль от имени пользователя root и проверяем наличие обновлений:
apt-get update && apt-get upgrade
Далее установим инструмент curl:
apt install curl -y
Затем запустим скачивание скрипта установки:
curl -O https://github.com/Evolutin/wireguard_install/master/wireguard-install.sh
chmod +x wireguard-install.sh
Появится строка ./wireguard-install.sh, жмем Enter и далее идем по пунктам конфигурации в консоли.
