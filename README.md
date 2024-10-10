# dpibypass
DPI yoluyla bloke edilen sitelere girmek mi istiyorsunuz? Doğru adresteniz.

### Gereksinimler
- https://github.com/ValdikSS/GoodbyeDPI/releases/tag/0.2.3rc3

### Kurulum
1. Ağ ayarlarınıza gidip DNS olarak 1.1.1.1 / 1.0.0.1 (Cloudflare DNS) giriniz.
2. GoodbyeDPI'yı indirip dosyaları bir yere çıkartın. Dosyaları silmeyeceğiniz bir yer olmak zorunda. (**C:\GoodbyeDPI** olabilir.)
3. **service_install_turkey_dnsredir.cmd** dosyasını o dizine taşıyın ve yönetici olarak çalıştırın.

Artık DPI yoluyla yasaklanmış her siteye girebilirsiniz.

### Kaldırmak
1. **service_remove.cmd** dosyasını (indireceğiniz goodbyedpi içinde) yönetici olarak çalıştırın.

Kontrol için services.msc'ye gidip GoodbyeDPI servisi duruyor mu bakabilirsiniz.

### Test Edilen Sistem
- İşletim sistemi: **Windows 11**
- İnternet sağlayıcı: **Turk Telekom**
- Site/Program: **Discord**
