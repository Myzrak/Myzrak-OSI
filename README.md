# Myzrak-OSI                                  #!/bin/bash

# Ekranı temizle
clear

# Görseldeki Birebir Somon / Turuncu Renk Kodu
ORANGE='\033[38;2;255;158;128m'
RESET='\033[0m'

# Ekran Çıktısı (Tamamı Görseldeki Renkte)
echo -e "${ORANGE}"
echo "Traceback (most recent call last):"
echo "  File \"<string>\", line 168, in <module>"
echo "  File \"<string>\", line 58, in main_menu"
echo "EOFError: EOF when reading a line"
echo ""
echo "███╗   ███╗██╗   ██╗███████╗██████╗  █████╗ ██╗  ██╗"
echo "████╗ ████║╚██╗ ██╔╝╚══███╔╝██╔══██╗██╔══██╗██║ ██╔╝"
echo "██╔████╔██║ ╚████╔╝   ███╔╝ ██████╔╝███████║█████╔╝ "
echo "██║╚██╔╝██║  ╚██╔╝   ███╔╝  ██╔══██╗██╔══██║██╔═██╗ "
echo "██║ ╚═╝ ██║   ██║   ███████╗██║  ██║██║  ██║██║  ██╗"
echo "╚═╝     ╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝"
echo ""
echo "           Myzrak OSINT Framework"
echo "========================================================"
echo "                       MAIN MENU                        "
echo "========================================================"
echo "1. Email Breach Lookup"
echo "2. Username Checker"
echo "3. Facebook Search"
echo "4. Youtube Search"
echo "5. Social Media Correlation"
echo "6. Configuration"
echo "7. Exit"
echo "========================================================"
echo ""

read -p "Seçiminiz [1-7]: " secim

case $secim in
    1)
        echo -e "\nEmail Breach Lookup çalıştırılıyor...${RESET}"
        ;;
    2)
        echo -e "\nUsername Checker çalıştırılıyor...${RESET}"
        ;;
    3)
        echo -e "\nFacebook Search çalıştırılıyor...${RESET}"
        ;;
    4)
        echo -e "\nYoutube Search çalıştırılıyor...${RESET}"
        ;;
    5)
        echo -e "\nSocial Media Correlation çalıştırılıyor...${RESET}"
        ;;
    6)
        echo -e "\nConfiguration çalıştırılıyor...${RESET}"
        ;;
    7)
        echo -e "\nÇıkış yapılıyor...${RESET}"
        exit 0
        ;;
    *)
        echo -e "\nGeçersiz seçim!${RESET}"
        ;;
esac
