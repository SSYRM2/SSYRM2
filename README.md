## **Kurulum Talimatları – Termux İçin**

Aşağıdaki komutları **sırasıyla** Termux'a girin:

```bash
# Python'u yükleyin
pkg install python

# Git'i yükleyin
pkg install git

# Depoyu klonlayın
git clone https://github.com/SSYRM2/SSYRM2

# Toolu etkinleştirelim
cd SSYRM2

# Yetkileri düzenleyin
chmod 777 *

# Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt

# Projeyi başlatın
python salvador.py
