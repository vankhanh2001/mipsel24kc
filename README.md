Các bước cài passwall cho router openwrt dùng chip mipsel_24kc:
Ssh vào router qua putty, CMD, powershell hoặc bất kì phần mềm nào ssh là được!
Sau đó chạy lần lượt các lệnh:
-	Opkg update
-	Opkg remove dnsmasq && opkg install dnsmasq-full
-	wget https://drive.google.com/drive/folders/1XJBGkh0_EIXpQKHGET0xU2sZZFIlWJY7?usp=sharing
Sau đó dùng lệnh “ls” để xem nó đã tải thành công hay chưa: Nếu hiện các mục ‘1.ipk 2.ipk .....’ là đã thành công, sau đó cài bằng lệnh sau:
-	Opkg install 1.ipk 2.ipk 3.ipk 4.ipk 5.ipk 6.ipk 7.ipk 8.ipk 9.ipk 10.ipk 11.ipk 12.ipk
Đợi chạy hết là thành công nhé hihi!

---------Văn Khánh---------
