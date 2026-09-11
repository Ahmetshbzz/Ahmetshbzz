<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img alt="Ahmet Şahbazoğlu — Backend & Systems Engineer" src="assets/hero-light.svg" width="100%">
</picture>

![Teknoloji yığını](assets/marquee.svg)

</div>

---

Go ve Python ile yüksek performanslı dağıtık sistemler inşa ediyorum. gRPC, OpenTelemetry ve event-driven mimarilerle production-grade servisler yazıyorum. Mobil tarafta React Native ve Swift ile native deneyimler geliştiriyorum; sistem seviyesinde ise eBPF ve düşük seviyeli ağ araçlarıyla çalışıyorum.

---

## Neler yapabiliyorum

İşin tamamını üstleniyorum: veri modeli ve doğruluğu, onu taşıyan çalışma zamanı ve insanların gerçekten dokunduğu arayüz. Aşağıdaki liste hangi müşteri için olduğunu değil, neyi sahiplenebildiğimi anlatır.

> İşlerin bir kısmı gizlilik kapsamında; bu yüzden isimler, kapsam ve sonuçlar bilinçli olarak dışarıda bırakıldı. Burada anlatılan yetenek.

| Yetenek | Kapsam |
|---|---|
| **Para doğruluğu gerektiren çekirdekler** | Tek bir minor unit'in sapmasına izin verilmeyen defterler: çift kayıtlı kayıtlar, tamsayı tutarlar, idempotency anahtarları ve maker-checker onayı. Mutabakat elle yapılan bir ritüel değil, kanıt üreten zamanlanmış bir iştir. |
| **Çok kiracılı platformlar** | Sınırları çizilmiş bağlamlara ayrılmış modüler monolitler, veritabanı seviyesinde zorlanan tenant izolasyonu ve fail-closed yapılandırma. Outbox, saga, dead-letter yönetimi ve leader election, tekrar denemeler altında asenkron işi doğru tutar. |
| **Gerçek zamanlı medya ve veri hatları** | Belirlenimci zaman damgalarıyla çok kaynaklı alım, kompozisyon, kodlama ve paketleme. Medya çekirdeği, akış başına süreç başlatmak yerine fork'lanmış kütüphanelere süreç içinde bağlanır. |
| **Kimlik ve yetkilendirme** | Passkey, ikinci faktör, anahtar rotasyonu ve mühürlü kimlik bilgisi. Makine erişimi ile insan oturumu ayrı kalır; güven, iletilen bir başlıktan değil doğrudan soketten kararlaştırılır. |
| **Yapay zeka ajan sistemleri** | Araç orkestrasyonu, vektör ve grafik depolar üzerinde kalıcı hafıza ve birinci sınıf arayüz olarak MCP sunucuları içeren çok servisli ajan platformları. |
| **Apple platform uygulamaları** | iOS ve macOS üzerinde native SwiftUI: menü çubuğu araçları, izin onboarding'i, Keychain destekli sırlar, konuşma ve ses yakalama ve incelemeden geçen dağıtım. |
| **Düşük seviyeli sistem ve güvenlik** | eBPF, TUN yığınları ve raw socket ile çekirdek ve ağ seviyesinde mühendislik; ayrıca yetkili değerlendirme: tehdit modelleme, tersine mühendislik ve tekrarlanabilir kanıt taşıyan raporlar. |
| **Tarayıcı otomasyonu ve kanıtlı araçlar** | Gerçek yapıyı çıkaran, onu belirlenimci biçimde yeniden kuran ve başarı iddia etmek yerine sonucu pixel diff ile kanıtlayan başsız otomasyon. |

![Bölüm ayracı](assets/divider.svg)

## Açık kaynak

| Proje | Ne yapar | |
|---|---|---|
| **[ctx-agent](https://github.com/Ahmetshbzz/ctx-agent)** | Universal Agent Context Protocol. AI ajanlarının kod tabanını çalıştırmadan anlamasını sağlar; tek binary, SQLite, offline. LLM yok, bulut yok. | `Rust` ★10 |
| **[anthropic-turkce-courses](https://github.com/Ahmetshbzz/anthropic-turkce-courses)** | Anthropic'in resmi eğitim materyallerinin Türkçe çevirisi. | `Jupyter` ★19 |
| **[voicman](https://github.com/Ahmetshbzz/voicman)** | macOS menü çubuğu dikte uygulaması. Global kısayol, Apple Speech ile canlı transkripsiyon, aktif uygulamaya yapıştırma. | `Swift` |
| **[web-search-mcp](https://github.com/Ahmetshbzz/web-search-mcp)** | Ajan öncelikli MCP sunucusu: çok sağlayıcılı web araması, içerik çıkarma ve tarayıcı otomasyonu. | `Python` |
| **[DockNest](https://github.com/Ahmetshbzz/DockNest)** | macOS Dock launcher'ı. Kurulu geliştirici araçlarını metadata'dan keşfeder, sürükle-bırak ile açar. Telemetri yok, ağ erişimi yok. | `Swift` |
| **[json](https://github.com/Ahmetshbzz/json)** | Tarayıcı eklentisi: JSON verisini okunaklı biçimde görüntüler. Açık/koyu tema, API performans metrikleri, dışa aktarma. | `JavaScript` |

## Teknoloji

**Backend**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)

**Frontend & Mobil**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Altyapı & Veritabanı**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

## Katkı grafiği

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ahmetshbzz/Ahmetshbzz/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ahmetshbzz/Ahmetshbzz/output/snake-light.svg">
  <img alt="Katkı grafiği" src="https://raw.githubusercontent.com/Ahmetshbzz/Ahmetshbzz/output/snake-dark.svg">
</picture>

</div>

---

## İletişim

<div align="center">

[![Website](https://img.shields.io/badge/ahmetshbzz.com-000000?style=for-the-badge&logo=globe&logoColor=white)](https://ahmetshbzz.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmet-%C5%9Fahbazo%C4%9Flu-77701917a)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/ahmetshbzx)
[![Email](https://img.shields.io/badge/Mail-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:ahmetcanshbz@proton.me)

</div>
