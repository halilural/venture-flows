# Gym Laundry — Spor Kıyafeti Abonelik Servisi

Kraków (Podgörze / Bonarka) için tasarlanmış, taşeron modeline dayalı bir spor
kıyafeti yıkama **abonelik servisi**nin operasyon akışı ve iş planı.

> Bu bir çamaşırhane değil — günde iki rota. Makine yok, vitrin yok, müşteri
> trafiği yok. İş dolabın kendisinde ve onu günde iki kez ziyaret eden rotada.

## Model özeti

Kapalı bir günlük döngü:

1. **07:00 — Topla.** Müşteri antrenman sonrası kirli setini gym'deki dolaba
   bırakır, app'e "kirli bırakıldı" sinyali gider, rota buna göre kurulur.
2. **08:00–15:00 — Yıkat (taşeron).** Boş kapasiteli ticari pralnia torbaları
   kapalı yıkar (6–9 zł/kg toplu tarife).
3. **16:00 — Geri koy.** Temiz set müşterinin dolabına döner, "setin hazır"
   bildirimi gider, döngü kapanır.

Yıkamayı sen yapmıyorsun; boş kapasiteli ticari pralnia yapıyor.

## Anahtar sayılar (2026 Kraków, netto)

| Metrik | Değer |
| --- | --- |
| Başlangıç yatırımı | 35–60k zł |
| Aylık sabit gider | 6–11k zł |
| Abone başı brüt marj | 69 zł |
| Başabaş abone sayısı | 60–80 |

**Fiyatlandırma:** B2B 149 zł/kişi/ay (tek fatura) · B2C 199 zł/ay.

## Büyüme fazları (her kapı bir "dur" fırsatı)

- **Faz 0 (0–3 ay):** Elle taşı. 1 gym, 20 pilot kullanıcı. Tek test: ödeme isteği.
- **Faz 1 (3–9 ay):** Sistemleştir. Retrofit elektronik kilit, kendi app, taşeron sözleşmesi.
- **Faz 2 (9–24 ay):** Ortak al, kurumsala geç. Kuru temizleme, B2B satış.
- **Faz 3 (24 ay+):** Ancak şimdi kendi makineni al.

Ana ilke: **Önce aboneyi bul, ekipmanı en son al.** Sıralamayı tersine çevirmek
tek başına riski 10 kat düşürüyor.

## İçerik

- [`index.html`](./index.html) — operasyon akışının tam, interaktif tek sayfalık
  görsel sunumu (24 saatlik döngü kadranı, akış aşamaları, para dağılımı ve
  büyüme kapıları).

Tarayıcıda `index.html` dosyasını açarak görüntüleyebilirsin.
