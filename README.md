![Zabbix](https://img.shields.io/badge/Zabbix-7.4%2B-red) ![License](https://img.shields.io/badge/License-MIT-blue) ![Platform](https://img.shields.io/badge/Platform-Windows%20Server-lightgrey)

[ 🌐 [English](#EN) ] | [ 🇹🇷 [Türkçe](#TR) ]

Windows DNS Server Performance Monitoring - Zabbix 7.4+

## EN

This repository contains a comprehensive Zabbix 7.4+ template optimized for deep monitoring of Windows DNS Server performance. With over 80 metrics, you can monitor your server's traffic, security, and replication status in real-time.

🌟 Key Features

    - Broad Metric Coverage: 80+ Performance Counters included.
    - Zabbix 7.4 Compatibility: Fully compliant with UUIDv4 standards and provided in YAML format.
    - Smart Grouping: Metrics are logically tagged as Traffic, Security, Replication, Memory, and Updates for streamlined monitoring.

📊 Monitored Categories

    Traffic     : UDP/TCP query counts, response speeds, and recursion details.
    Security    : Packets blocked by Response Rate Limiting (RRL) or dropped due to policy.
    Replication : Zone Transfer (AXFR/IXFR) success/failure states and Notify traffic.
    Memory	    : Database node, caching, and UDP/TCP message memory usage.

🛠 Installation

    - Download the template_WindowsDNS.yaml file.
    - In the Zabbix Web UI, navigate to Data Collection -> Templates -> Import.
    - Select the downloaded file and click Import.
    - Navigate to your Windows Host and link this template.

📝 License

    This project is licensed under the MIT License. Feel free to use, modify, and distribute it.

## TR
Bu repo, Windows DNS Server performansını derinlemesine izlemek için optimize edilmiş kapsamlı bir Zabbix 7.4+ şablonu (template) içerir. 80'den fazla metrik ile sunucunuzun trafik, güvenlik ve replikasyon durumunu anlık olarak takip edebilirsiniz.

🌟 Önemli Özellikler

    - Geniş Metrik Kapsamı: 80+ performans sayacı (Performance Counters).
    - Zabbix 7.4 Uyumluluğu: UUIDv4 standartlarına tam uyumlu ve YAML formatında.
    - Akıllı Gruplandırma: Metrikler; Traffic, Security, Replication, Memory ve Updates olarak tag'lenmiştir.

📊 İzlenen Kategoriler

    Traffic    :  UDP/TCP sorgu sayıları, yanıt hızları ve özyineleme (recursion) detayları.
    Security   :  RRL (Response Rate Limiting) tarafından engellenen veya politika gereği düşen paketler.
    Replication:  Zone Transfer (AXFR/IXFR) başarı ve hata durumları, Notify trafikleri.
    Memory     :  Database node, caching ve UDP/TCP mesaj bellek kullanımları.

🛠 Kurulum

    - template_WindowsDNS.yaml dosyasını indirin.
    - Zabbix arayüzünde Data Collection -> Templates -> Import adımlarını izleyin.
    - Dosyayı seçin ve içe aktarın.
    - İlgili Windows Host'unuza gidin ve bu şablonu (Template) bağlayın (Link).

📝 Lisans (License)

    Bu proje MIT License ile lisanslanmıştır. Özgürce kullanabilir ve geliştirebilirsiniz.
