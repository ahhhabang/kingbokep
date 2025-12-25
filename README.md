### ℹ️ INFORMASI UNTUK ANDROID 
Jangan menginstall di scdard karena 100% tidak akan berfungsi

## 📥 INSTALASI

```bash
# Update package termux
pkg update && pkg upgrade -y

# Install python dan git
pkg install python -y
pip install requests
pip install beautifulsoup4
pkg install git -y

# Download script order-kuota
git clone https://github.com/ahhhabang/kingbokep.git

# Masuk ke directory
cd order-kuota

# Jalankan aplikasi
python run.py
