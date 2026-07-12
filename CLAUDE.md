# CLAUDE.md — Suphi Ramazanoğlu / EVOLIXO Proje Alanı

Her Claude Code oturumu bu dosyayı okuyarak başlar.
Aşağıdaki kurallar memory'den önce gelir; çelişki varsa burası kazanır.

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
C:\Users\supra\OneDrive\1_Documents\1_Kariyer\1_3_Triova_sirket\8_Triova_AI_agent\dijital_olgunluk_platformu\
```
- **Durum:** v1.4 canlı, Faz 2 tamamlandı
- **Port:** 8503 (Streamlit)
- **Sonraki:** Şifremi unuttum akışı, rate limiting, Faz 3 = Next.js + FastAPI
- **Supabase:** free tier, proje ID memory'de
- **GitHub:** github.com/supram47/dijital-olgunluk-platformu

### Carousel & LinkedIn İçerik Üretimi
```
C:\Users\supra\OneDrive\1_Documents\1_Kariyer\1_2_suphiramazanoglu.com\Hedef kitle analizi\Metricool\metricool-carousel-agent\
```
- Brand dosyası: `brands/suphi-ramazanoglu/BRAND.md`
- Render: `node .claude/skills/generate-carousel/render.js "export/<klasör>"`
- Upload: `node scripts/upload-catbox.mjs "export/<klasör>"`
- Metricool brandId: **6370980**, timezone: **Europe/Istanbul**
- Planlama slotu: **Salı ve Perşembe 11:00**
- createScheduledPost → **TEK çağrıda** facebook+instagram+linkedin birlikte

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

**Öncelik sırası:** Göreve özgü MCP > Claude Browser (web) > Bash

---

## GitHub Sync Alışkanlığı

Her önemli güncelleme sonrası **GitHub'a push et**. Repo:
```
github.com/supram47/dijital-olgunluk-platformu
```
Commit öncesi `git status` çalıştır, hassas dosya (.env, key) kontrolü yap.

---

## Dil

- **Türkçe** — konuşma, açıklama, strateji tartışmaları
- **İngilizce** — LinkedIn/sosyal medya içerikleri (varsayılan), teknik terimler
- Türkçe post istisnai (özel talep gerekir); varsayılan içerik dili **İngilizce**

---

## LinkedIn İçerik Şablonu

```
[Hook — tek satır, somut veya paradoksal]

[2-3 satır bağlam — "I watched / We had / I saw"]

[Temel içgörü]

[→ bullet points — max 3-4]

[Kapanış sorusu]

[#DigitalTransformation #AgileTransformation #Leadership #ChangeManagement]
```

Onaylı istatistikler: $20M+, 26 profesyonel, 4 ülke, %18 warranty, %20+ verimlilik, $4M program 3 hafta önde.

---

## Çalışma Tarzı

- Basit soruya kısa cevap — bullets veya tablo, paragraf değil
- Kod değişikliği önerirken sebebini söyle (ne yaptığını değil, neden)
- Taslak/öneri için onay al, sonra uygula
- Büyük değişikliklerde adım adım git; tek seferde her şeyi değiştirme
- Gereksiz dosya oluşturma — mevcut dosyaları düzenle
