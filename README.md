Windows DNS Server Performance Monitoring - Zabbix 7.4+

Bu repo, Windows DNS Server performansını derinlemesine izlemek için optimize edilmiş kapsamlı bir Zabbix 7.4+ şablonu (template) içerir. 80'den fazla metrik ile sunucunuzun trafik, güvenlik ve replikasyon durumunu anlık olarak takip edebilirsiniz.

🌟 Önemli Özellikler (Key Features)
    - Geniş Metrik Kapsamı: 80+ performans sayacı (Performance Counters).
    - Zabbix 7.4 Uyumluluğu: UUIDv4 standartlarına tam uyumlu ve YAML formatında.
    - Akıllı Gruplandırma: Metrikler; Traffic, Security, Replication, Memory ve Updates olarak tag'lenmiştir.

📊 İzlenen Kategoriler (Monitored Categories)
  Traffic    :  UDP/TCP sorgu sayıları, yanıt hızları ve özyineleme (recursion) detayları.
  Security   :  RRL (Response Rate Limiting) tarafından engellenen veya politika gereği düşen paketler.
  Replication:  Zone Transfer (AXFR/IXFR) başarı ve hata durumları, Notify trafikleri.
  Memory      : Database node, caching ve UDP/TCP mesaj bellek kullanımları.

🛠 Kurulum (Installation)
    template_WindowsDNS.yaml dosyasını indirin.
    Zabbix arayüzünde Data Collection -> Templates -> Import adımlarını izleyin.
    Dosyayı seçin ve içe aktarın.
    İlgili Windows Host'unuza gidin ve bu şablonu (Template) bağlayın (Link).

📝 Lisans (License)
Bu proje MIT License ile lisanslanmıştır. Özgürce kullanabilir ve geliştirebilirsiniz.
