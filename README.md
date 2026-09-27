# design-system

LibreUniversity tasarım sistemi: ilkeler, tasarım tokenları, erişilebilir bileşenler.

## İçerik

- Tasarım kaynakları: [Penpot](https://penpot.app) (özgür, self-hosted çalışabilen tasarım aracı)
- `@libre-university/tokens`: renk, tipografi, boşluk tokenları (web ve mobilde ortak)
- `@libre-university/ui`: React bileşen kütüphanesi
- Storybook ile bileşen kataloğu

## İlkeler

- WCAG 2.1 AA erişilebilirlik
- Üniversitelerin kendi kurumsal renklerini tema ile uygulayabilmesi (çok kiracılı kullanım)
- Açık lisanslı yazı tipleri, self-hosted sunum

## Fazlara Göre İşler

| Faz | Bu repoda yapılacaklar |
| --- | --- |
| Faz 0 | Tasarım ilkeleri, Penpot çalışma alanı, tasarım tokenları, Storybook ve CI |
| Faz 1 | Temel bileşenler, uygulama kabuğu, kurumsal tema desteği |
| Faz 2 | Tablo, not giriş tablosu, takvim, onay akışı bileşenleri |
| Faz 3 | React Native uyarlaması, erişilebilirlik denetimi ve kullanıcı testleri |
| Faz 4+ | İhtiyaca göre yeni bileşenler |

Ayrıntılı ve işaretlenebilir liste: [ROADMAP.md](ROADMAP.md). Fazlar [ana yol haritası](https://github.com/Libre-University/docs/blob/main/ROADMAP.md) ile hizalıdır. Açık işler için `phase:*` etiketlerine bakın.

## Katkı

Katkı rehberi, davranış kuralları ve güvenlik politikası organizasyon genelinde [`.github`](https://github.com/Libre-University/.github) reposundadır. Mimari kararlar [`docs`](https://github.com/Libre-University/docs) reposundaki ADR'lerle alınır.

## Lisans

Bu proje [GNU Affero Genel Kamu Lisansı v3.0 veya sonrası](LICENSE) (AGPL-3.0-or-later) ile lisanslanmıştır. Ağ üzerinden hizmet olarak sunulan değiştirilmiş sürümlerin kaynak kodu da kullanıcılarla paylaşılmalıdır ([ADR-0002](https://github.com/Libre-University/docs/blob/main/docs/adr/0002-prefer-agpl-3-or-later-license.md)).
