# shadowsocksR常見FAQ指南（非常重要） :facepunch:

### 2019年11月份GFW再次升級，據說VPN（shadowsocks，shadowsocksR）被攔截的很厲害經常出現斷流的現象，但是目前已經新對策出現

-----

# 常見被牆的方法 :question:

- :pushpin: 屏蔽IP
- :pushpin: 封port

---

### 如何檢測自己的IP是被牆的哪種方式呢 :question:

-  :pencil2: ping 一下自己的IP，如果顯示超時即被GFW攔截了。另一種方式就是國內ping不通，國外ping的通就是也是被GFW攔截了
-  :pencil2: ping完有顯示延遲則是port被攔截了，換一下shadowsocksR，shadowsocks端口就能正常使用了

---

### 具體拯救措施 :wave:

- IP被封：搭建v2ray,利用域名中轉恢復被牆的IP :wave:
>  :wave: 腳本參考：https://github.com/wulabing/V2Ray_ws-tls_bash_onekey


- 端口被牆：修改json文件，逗逼的json文件修改port： vi /usr/local/shadowsocksr/mudb.json 保存退出即可 :exclamation:
> :exclamation: 
逗比的脚本：wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/ssrmu.sh && chmod +x ssrmu.sh && bash ssrmu.sh

---

# 常规命令 :wave:

- ：wq！ 保存退出 :wave:
- :q! 退出 :wave:
- cd 打開 :wave:
- ls 展視 :wave:
- cat 查看 :wave:
- vi 編輯 :wave:
- i 插入 :wave:
- x 刪除 :wave:

---

### 聯繫方式 :bell:

- Telegram：https://t.me/xwring :point_left:
- Line：chryax :point_left:
- :email: info@chryax.com.tw :point_left:
- Facebook粉專：https://www.facebook.com/jsrwon :point_left:
- 個人blog：https://vschk.wordpress.com/ :point_left:
- 微信公眾號 :point_left:


![image](https://github.com/hkjswong/shadowsocksR-setup/blob/master/%E5%BE%AE%E4%BF%A1%E5%85%AC%E7%9C%BE%E8%99%9F.jpg)

