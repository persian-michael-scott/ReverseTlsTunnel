**سلام دوستان.
از کد شاخه master فورک گرفتم توی ریپازیتوری خودم و با توجه به راهنمایی های radkesvat قابلیت تغییر دو تا آرگومان**
> --connection-age
> --parallel-cons

**رو به اسکریپت اضافه کردم .
میتونید مقادیر دلخواه رو انتخاب کنید**


 # آپدیت : قابلیت تانل چند سرور ایران با یک سرور خارج در اسکریپت قرار داده شد.

# نکته :
- در هیدیفای برای ساخت کانفیگ relay mode نزنید . old-direct mode بزنید و قسمت دامنه رو یه سایت ایرانی پرترافیک بذارید و قسمت اجبار رو یه ساب دامنه که پشتش ایپی سرور داخلی هست. نوع کانفیگ هم vmess http tcp خوب جواب داده واسه من.

# نحوه استفاده 

 ## روش اول (نصب با اسکریپت)
 
 ```
 cd && bash <(curl -fsSL https://raw.githubusercontent.com/persian-michael-scott/ReverseTlsTunnel/master/scripts/RtTunnel.sh)
 ```
 
 ![1](https://raw.githubusercontent.com/persian-michael-scott/ReverseTlsTunnel/master/RTT.png)
 
 - [آموزش در کانال @IR_TECH](https://youtube.com/watch?v=1mj1fhA2X6s)
- به صورت سرویس نصب میشود 
- از پورت 23 به بالا میتوانید استفاده کنید. 
- پورت 1 تا 22 قابل استفاده نیستند. 
- از SNI و پسورد یکسان روی هر دو سرور جهت اتصال به یکدیگر استفاده کنید.
- فایل RTT پس از کامپایل در مسیر ReverseTlsTunnel/dist ذخیره میشود.
 

اینترنت یا برای همه یا برای هیچکس!

به امید آزادی

