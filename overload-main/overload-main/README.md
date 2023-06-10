<h1 align="center">📡 Công cụ DDOS (Lớp 7) </h1> 
<div align="center">
<img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg"> <img src="https://svgshare.com/i/ZhY.svg"> <img src="https://img.shields.io/github/forks/7zx/overload?style=social&label=Fork&maxAge=2592000"> <img src="https://img.shields.io/github/stars/7zx/overload?style=social&label=Star&maxAge=2592000"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"> 
</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/7zx/overload/main/img/logo.png" width="200" height="200">
</p>

# :computer: Cửa sổ chính
<p align="center">
  <img src="https://raw.githubusercontent.com/tanjilk/overload/main/img/imgshow.png">
</p>

# 🌙 Cài đặt


<h2>Windows</h2> <img src="https://cdn.iconscout.com/icon/free/png-256/windows-221-1175066.png" width="50" height="50">  

  - Cài đặt Python 3.8 [tại đây](https://www.python.org/downloads/release/python-38)
  - Mở trình cài đặt và nhấp vào: `add python to PATH`
  - Tải xuống overload <a href="https://github.com/DauDau432/overload/archive/refs/heads/main.zip" target="blank">tại đây</a>
  - Mở cmd hoặc PowerShell trong thư mục overload
  - Chạy lệnh này: `pip install -r requirements.txt`  

 <h2>Linux</h2><img src="https://raw.githubusercontent.com/8fn/overload/main/img/linux-icon-28166.png" width="50" height="50">

```
sudo apt update
sudo apt install python3 python3-pip git -y
git clone https://github.com/7zx/overload
cd overload/
pip3 install -r requirements.txt or python -m pip install -r requirements.txt
```

<h2>Termux</h2><img src="https://brandslogos.com/wp-content/uploads/images/large/terminal-logo.png" width="50" height="50">  

```
pkg update
pkg install python3 python3-pip git -y
git clone https://github.com/7zx/overload
cd overload/
pip3 install -r requirements.txt
```

## ❓ Cách sử dụng
Lệnh cơ bản để chạy overload như sau.  

```
python3 overload.py --time XXX --threads XXX --target [URL] --method HTTP
```

Thí dụ: 

```
python3 overload.py --time 5000 --threads 10000 --target https://www.abc.com/ --method HTTP
```
