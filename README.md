# dpibypass
DPI yoluyla bloke edilen sitelere girmek mi istiyorsunuz? Doğru adresteniz.

### Gereksinimler
- https://github.com/ValdikSS/GoodbyeDPI/releases/tag/0.2.3rc3

### Adımlar
1. Ağ ayarlarınıza gidip DNS olarak 1.1.1.1 / 1.0.0.1 (Cloudflare DNS) giriniz.
2. GoodbyeDPI'yı indirip dosyaları bir yere çıkartın.
3. **service_install_turkey_dnsredir.cmd** dosyasını o dizine taşıyın ve yönetici olarak çalıştırın.

Artık DPI yoluyla yasaklanmış her siteye girebilirsiniz. Servisi kaldırmak için **service_remove.cmd** dosyasını (indireceğiniz goodbyedpi içinde) yönetici olarak çalıştırın.

### Test Edilen Sistem
- İşletim sistemi: **Windows 11**
- İnternet sağlayıcı: **Turk Telekom**
