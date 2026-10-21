# CLAUDE.md — Suphi Ramazanoğlu / EVOLIXO Proje Alanı

Her Claude Code oturumu bu dosyayı okuyarak başlar.
Aşağıdaki kurallar memory'den önce gelir; çelişki varsa burası kazanır.

**Kanıt & içerik referans dosyaları (istatistik çelişkisinde bunlar kazanır):**
- `proof.md` — tüm onaylı istatistikler, sertifikalar, ödüller (bu dizinde)
- `C:\Users\Suphi Ramazanoğlu\OneDrive\1_Documents\1_Kariyer\1_1_CV_Kariyer\4_Linkedin\Linkedin\best_posts.md` — kanıtlanmış kazanan postlar, hook formülleri, yayın saati verileri

---

## Kim

**Suphi Ramazanoğlu** — Digital, Agile & Program Governance Consultant. İstanbul merkezli, 20+ yıl automotive electronics ve dijital dönüşüm. C-suite seviye. **Geliştirici değil — domain expert ve ürün vizyoneri.**

**Rol dağılımı:**
- Domain içeriği, örnekler, vaka, sektör kararı → **Suphi**
- Kod, UI, API, araç → **Claude Code**
- Strateji ve konumlandırma → **Birlikte**

---

## Marka

| Alan | Değer |
|------|-------|
| Üst marka | **EVOLIXO** (eski: Triova — asla kullanma) |
| Danışmanlık markası | Fonksiyon 360 |
| SaaS ürünü | **DigiScore by EVOLIXO** |
| Domain | evolixo.com (Hostinger, 24 Haz 2026) |
| Şirket yapısı | Şahıs şirketi → A.Ş. yol haritası (DigiScore MRR 10K TL hedefinde) |

---

## Aktif Projeler ve Dosya Yolları

### DigiScore — Dijital Olgunluk Platformu
```
C:\Users\Suphi Ramazanoğlu\OneDrive\1_Documents\1_Kariyer\1_3_Triova_sirket\8_Triova_AI_agent\dijital_olgunluk_platformu\
```
- **Durum:** v1.4 canlı, Faz 2 tamamlandı
- **Port:** 8503 (Streamlit)
- **Sonraki:** Şifremi unuttum akışı, rate limiting, Faz 3 = Next.js + FastAPI
- **Supabase:** free tier, proje ID memory'de
- **GitHub:** github.com/supram47/dijital-olgunluk-platformu

### Carousel & LinkedIn İçerik Üretimi
```
C:\Users\Suphi Ramazanoğlu\OneDrive\1_Documents\1_Kariyer\1_2_suphiramazanoglu.com\Hedef kitle analizi\Metricool\metricool-carousel-agent\
```
- Brand dosyası: `brands/suphi-ramazanoglu/BRAND.md`
- Render: `node .claude/skills/generate-carousel/render.js "export/<klasör>"`
- Upload: `node scripts/upload-catbox.mjs "export/<klasör>"`
- Metricool brandId: **6370980**, timezone: **Europe/Istanbul**
- Planlama slotu (5 Ekim 2026'dan itibaren, platform başına haftada 1 post): **LinkedIn+Facebook Salı 11:00, Instagram Perşembe 11:00**
- createScheduledPost → **İKİ ayrı çağrı**: LinkedIn+Facebook birlikte, Instagram ayrı (ayrı caption; tek çağrıda yalnızca bir caption yayınlanır, 14 Eylül 2026 bulgusu)

### Günlük Brifing (Make.com → HTML)
- F360 mailler → outlook.office.com, Kişisel → outlook.live.com
- Gerçek senaryoda Graph API `webLink` kullanılacak

---

## Kesin Kurallar — İçerik ve Konumlandırma

### ASLA KULLANMA
- `—` em dash (ne metinde ne kodda ne HTML'de)
- **SPICE / TISAX** — geçmiş CVe'de var, ama pazarlama/satış/içerikte asla
- **Ford, Daiichi, Stellantis, Iveco** gibi şirket isimleri → yerine: "a global automotive program", "a Tier-1 supplier", "an automotive OEM"
- Fabricated alıntı veya kaynak gösterilemeyen yüzde istatistiği
- "game-changer / leverage synergies / unlock your potential / You must / You should"
- "Ben Scrum Master olarak sprint koştum" tarzı ifadeler
- "15 years" → her zaman **"20+ years"**
- LinkedIn jargonu

### Agile Uzmanlık Sınırı
- **Güçlü (kanıtlanmış):** Kanban (KMP I/II/Pro), Hybrid Agile-Predictive, Program Governance
- **Teorik:** Scrum (PSM I var, derin uygulama yok)
- **Güvenli dil:** "I've watched / I've seen / In my experience" — observer/architect konumu
- **Kaçın:** "I ran sprints / I was Scrum Master"

### Otomotiv Pozisyonu
- Otomotiv **kapsam içinde** ama tek sektöre sıkışılmayacak
- Genel B2B dijital dönüşüm diliyle otomotiv deneyimini **kanıt** olarak kullan, **merkez** olarak değil

---

## MCP Araç Haritası

| Görev | MCP / Araç |
|-------|------------|
| Outlook mail okuma | `mcp__8b031f6b__outlook_email_search` |
| Outlook takvim | `mcp__8b031f6b__outlook_calendar_search` |
| Make.com senaryo yönetimi | `mcp__5c92b09c__scenarios_*` |
| Supabase sorgu/migrasyon | `mcp__5f7bf739__execute_sql`, `apply_migration` |
| Metricool planlama | `mcp__d1f30e10__createScheduledPost` |
| HubSpot CRM | `mcp__bf8598c0__*` |
| Canva tasarım | `mcp__c9058dc7__*` |
| Gamma sunum | `mcp__446fc9f7__*` |
| Canlı web arama / trend / rakip / sosyal medya verisi | `mcp__b915e6d6__search_engine`, `web_data_*` (LinkedIn, Instagram, TikTok, X, YouTube, Facebook, Reddit) — Bright Data, aylık 5.000 kredi ücretsiz havuz |
| Motion (görev/takvim otomasyonu) | ücretsiz plan |

**Öncelik sırası:** Göreve özgü MCP > Claude Browser (web) > Bash

---

## GitHub Sync Alışkanlığı

Her önemli güncelleme sonrası **GitHub'a push et** (repo: DigiScore bölümünde). Commit öncesi `git status` çalıştır, hassas dosya (.env, key) kontrolü yap.

---

## Dil

- **Türkçe** — konuşma, strateji ve LinkedIn/sosyal medya içeriği (varsayılan, Ağu 2026'dan itibaren). Teknik terimler İngilizce olabilir.
- İngilizce post istisnai, özel talep gerektirir

---

## LinkedIn İçerik Şablonu

```
[Hook — tek satır, somut veya paradoksal]

[2-3 satır bağlam — "Gördüm / İzledim / Deneyimledim / Çalıştığım programlarda"]

[Temel içgörü]

[-> bullet points — max 3-4]

[Kapanış sorusu — sınırlı seçenekli, somut]

[#DijitalDönüşüm #ÇevikDönüşüm #Liderlik #DeğişimYönetimi]
```

Onaylı istatistikler: $20M+, 26 profesyonel, 4 ülke, %18 warranty, %20+ verimlilik, $4M program 3 hafta önde.

---

## Çalışma Tarzı

- Basit soruya kısa cevap — bullets veya tablo, paragraf değil
- Kod değişikliği önerirken sebebini söyle (ne yaptığını değil, neden)
- Taslak/öneri için onay al, sonra uygula
- Büyük değişikliklerde adım adım git; tek seferde her şeyi değiştirme
- Gereksiz dosya oluşturma — mevcut dosyaları düzenle
- Web/tarayıcı kontrolünde önce metin araçları (`get_page_text`, `read_page`, `find`); ekran görüntüsü yalnızca görsel doğrulama gerekiyorsa
- Ajan/alt ajan raporları en fazla 10 satır; veritabanı listelemelerinde `where` filtresi ve `limit` kullan, tüm koleksiyonu dökme
- Hesap içeren her teklif/rapor: toplamı alt kalemlerden yeniden topla ve doğrula, formülü yazmakla yetinme
- Teslim edilecek her dosyayı (docx, görsel, rapor) göndermeden önce görsel olarak kontrol et — taşma, kesik metin, bozuk karakter var mı bak
- Netleşmemiş rakam/varsayımı açıkça boş/işaretli bırak, uydurma; "bu alan X formülüyle hesaplanacak" gibi net not düş
- n8n/otomasyon işlerinde: workflow'u yazmakla iş bitmiş sayılmaz, gerçek ortamda çalıştırıp sonucu göster; para/silme/dış mesaj gönderme gibi geri alınamaz adımlarda önce onay iste
- Belirsiz "duruma göre değişir" cevabıyla kapatma — kararı hangi eşiğin/koşulun değiştireceğini söyle
- Bilgiyi dağıtık maddeler halinde bırakma — neden, sonuç, seçenek, risk ve öneri arasındaki bağı kur, tek tek doğru ama birbirinden kopuk parçalar sunma
- Sözleşme/teklif/dava metinlerinde feragat, ibra, kabul veya yeni yükümlülük doğuran ifadeleri özellikle işaretle — hak kaybı riski taşıyan dili sessizce geçirme
- Gizli anahtar/credential asla düz metinde/kodda bırakma — n8n'de credential store kullan, PDF/dokümanlarda açık anahtar görürsen hemen uyar
- Büyüme/pazarlama önerisi verirken önce birim ekonomisini göster (CAC, kâr marjı, başabaş noktası) — ciro veya görünürlük artışını otomatik kâr sanma
- Kaynak/zaman kısıtlı kararlarda (hangi projeye öncelik, hangi kampanyaya bütçe) seçilmeyen alternatifin fırsat maliyetini de göster
