# Install
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && rm -f setup.sh && apt-get update -y && apt-get upgrade -y && apt install screen zip ftp bzip2 sudo gzip coreutils wget curl neofetch -y && wget -q "https://raw.githubusercontent.com/ayaze01/free-autoscript-vpn/main/setup.sh" && chmod +x setup.sh && ./setup.sh
