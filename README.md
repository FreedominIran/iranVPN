# راه اندازی
برای راه اندازی یک فیلتر شکن نیاز به **سرور مجازی** و نرم افزار راه اندازی **فیلتر شکن** دارید.


## سرور مجازی
ساده و سریع ترین دیتاسنتر ها برای تهیه سرور مجاری [Hetzner](https://console.hetzner.cloud) [OVH](https://www.ovhcloud.com/en/vps/) [Vultr](https://www.vultr.com/) [Oracle](https://www.oracle.com/cloud)  هستند.

اما در [whtop](https://www.whtop.com/directory/category/vps/os/linux) لیست کاملی از بیش از 2500 سرور مجازی وجود داره که قابل بررسی و انتخاب هستند. 


## نرم افزار راه اندازی فیلتر شکن
**راحت ترین و کامل ترین** نرم افزار راه فیلترشکن  [hiddify](https://github.com/hiddify/hiddify-config) هست. مخصوص ایران راه اندازی شده و به سرعت به روز و توسعه داده میشه؛ میتونید با زدن یک خط دستور اون رو در سرور مجازیتون نصب و ازش استفاده کنید.

 پنل های دیگه ای هم هستند با راه اندازی سختر و کارایی مشابه یا کمتر: [SSPanel](https://github.com/Anankke/SSPanel-Uim) [v2board](https://github.com/v2board/v2board)

پنل هایی که بایک خط دستور نصب میشن: [x-ui](https://github.com/vaxilu/x-ui) [trojanpanel](https://github.com/trojanpanel/install-script)

همینطور اسکریپت هایی که پرتوکل ها رو اجرا میکنند ولی سایت [UI] ندارند:
 [SSPanel](https://github.com/Anankke/SSPanel-Uim) [install-script](https://github.com/trojanpanel/install-script)

# پیج های یوتوب
تقریبا آموزش راه اندازی بیشتر پرتوکل ها و نرم افزار های فیلترشکن رو روی این پیج ها به فارسی پیدا میکند:

[MortezaBashsiz](https://www.youtube.com/@MortezaBashsiz) [iAghapour](https://www.youtube.com/@iAghapour) [MrBluepoint](https://www.youtube.com/@MrBluepoint)

[CertifiedTrueCopy](https://www.youtube.com/@CertifiedTrueCopy) [freenetforiran](https://www.youtube.com/@freenetforiran) [webdy](https://www.youtube.com/@webdy)

# پرتوکل ها

پرتوکل های زیر توسط بیشتر اپراتور ها به سادگی محدود شدن یا میشند  
(به این معنی که نمیتونید با این پروتوکل ها مستقیم به سرور خارج تونل کنید و نیاز به سرور یا CDN ایران دارید.)

>Sofether OpenVPN SSTP PPTP L2TP/IPSec Wiregard Kryio


با تکنولوژی مبهمسازی [obfuscation] میشه
ترافیک شبکه رو شبیه یک ترافیک معمولی کرد ( تا مشابه یک تونل نباشه )
این طوری شرایط برای بازرسی عمیق بسته ها [DPI] و مسدود کردن سرور فیلتر شکن ها سخت تر میشه.

پرتوکل های زیر تکنولوژی مبهمسازی را بهتر پشتیبانی میکنند کمی دیرتر و سخت تر توسط اپراتور ها شناسایی و محدود میشند.

>HTTP SOCKS VLESS VMESS WS SS TROJAN HYSTERIA BROOK OpenVPN

----
اگه مطلب مفیدی هست که دوست دارید اینجا باشه برام بفرستید، همینطور هر سوالی دارید میتونید مطرح کنید.

freedominIran@dnmx.org
