# Xtream-UI By Mohamed Rady

امر التثبيت

apt update && apt upgrade -y && apt-get install python2 -y && apt install python3 -y && apt-get update && apt-get upgrade -y

--------------------------------------------------------

wget https://bitbucket.org/mohamedrady24/ubuntu-20-04/downloads/install.py && chmod 0777 install.py

sudo python2 install.py

--------------------------------------------------------

التشغيل

crontab -e

@reboot /home/xtreamcodes/iptv_xtream_codes/start_services.sh
