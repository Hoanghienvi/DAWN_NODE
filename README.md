### Tool dawn phiên bản đầy đủ sử dụng python (proxy) | version Python 3.10+
```


✔️ Ping node

✔️ Auto task

✔️ Auto login

✔️ Đa luồng
```
 ### 
1️⃣ cài các module cần thiết
```
pip install -r requirements.txt hoặc pip3 install -r requirements.txt
```
### 
2️⃣ Setup dữ liệu đầu vào:
```
config/data/register.txt lưu thông tin tài khoản để đăng ký, định dạng: email:password

config/data/farm.txt lưu thông tin tài khoản để mining( treo node), định dạng: email:password

config/data/reverify.txt lưu thông tin tài khoản để reverify, định dạng: email:password

config/data/proxies.txt lưu thông tin proxy, định dạng:

http://user:pass@ip:port

http://ip:port:user:pass

socks5://user:pass@ip:port
```
### 
3️⃣ Cấu hình lại thông tin bot trong file config/settings.yaml. Trong đó ae cần quan tâm tới captcha_module và 2 key captcha đi kèm. Có 2 options là anticaptcha và 2captcha. AE dùng captcha nào thì nhập api_key của captcha đó vào.
###
4️⃣ Chạy tool bằng lệnh :

Windown or Termux:

python run.py

MacOs or linux:

python3 run.py
