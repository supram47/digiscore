# MAP.md: hangi dosya doğru kaynak?

Amaç: oturum başında yanlış veya eski dosyayı okuyup token harcamamak. Bir bilgi iki yerde varsa **Kanonik** sütunundaki kazanır, diğerleri kopyadır.
Son doğrulama: 8 Ekim 2026. Güncelle: yeni sistem kurulunca veya bir kaynak taşınınca.

## Kurallar ve kanıt

| Konu | Kanonik kaynak | Kopya / türev |
|---|---|---|
| Çalışma kuralları, marka, yasaklar | `CLAUDE.md` (bu klasör) | Memory (`.claude/projects/.../memory`), çelişirse CLAUDE.md kazanır |
| Onaylı istatistikler, sertifikalar | `proof.md` | CLAUDE.md içindeki kısa liste |
| Kazanan post formülleri | `1_1_CV_Kariyer\4_Linkedin\Linkedin\best_posts.md` | |
| Kişisel marka sesi, renk, yasaklar | `...\metricool-carousel-agent\brands\suphi-ramazanoglu\BRAND.md` | |

## Ajanlar ve görevler

| Konu | Kanonik kaynak | Kopya / türev |
|---|---|---|
| Ajan listesi ve sayısı | `AJAN_ENVANTERI.md` | Dashboard Ajan Kadrosu sekmesi (aylık denetimle eşitlenir, geride kalabilir) |
| IA, FL, DS, TKF ajan davranışı | `.claude/agents/*.md` | Dashboard'daki açıklamalar |
| Zamanlanmış görev davranışı | `C:\Users\Suphi Ramazanoğlu\.claude\scheduled-tasks\<id>\SKILL.md` | Dashboard'daki görev tablosu |
| Teklif motoru rolleri | `TEKLIF_MOTORU_KADRO.md` | |

## Dashboard (Girişimcilik Danışma Kurulu)

| Konu | Kanonik kaynak | Kopya / türev |
|---|---|---|
| Sayfa (arayüz) | Canlı artifact `ce304224-6704-49d2-a3e7-b3ef2e21579b` (okumak için Artifact aracı, `read`) | `girisimcilik-danisma-kurulu.html` (bu klasör, 4 Ekim 2026 tarihli yedek, her zaman eski olabilir) |
| Veri | Artifact db: `linkedin_listings`, `freelance_listings`, `destek_firsatlari`, `haftalik_istihbarat`, `nis_radar_reports`, `linkedin_meta/budget`, `linkedin_requests` | Sayfa içine gömülü veri yoktur, brifing hariç (`PREFETCHED` satırı, günlük görev yeniler) |
| Günlük brifing | Supabase `daily_briefings` | Sayfadaki `PREFETCHED` yedeği |
| İstihbarat veri çekme | `youtube_radar/fetch.mjs`, `youtube_radar/intel_fetch.mjs` | |

Yayın kuralı: artifact'a yeni sürüm göndermeden önce canlı sürümü oku (brifing görevi sayfayı kendisi günceller), yoksa yayın reddedilir.

## Kişisel belgeler

| Konu | Kanonik kaynak | Kopya / türev |
|---|---|---|
| CV | `1_1_CV_Kariyer\SUPHIRAMAZANOGLUCV261002.pdf` | Önceki PDF sürümleri aynı klasörde, arşiv sayılır |
| LinkedIn banner | `Downloads\linkedin_banner_A_canli2_1584x396.png` (seçilirse) | Diğer banner dosyaları denemedir |

## Alt projeler (kendi repoları var, `.gitignore` ile dışarıda)

`dijital_olgunluk_platformu/` (DigiScore, GitHub: supram47/dijital-olgunluk-platformu), `kredi-kart-analiz/`, `sahis-sirketi-masraf-takip/`, `metricool-carousel-agent/` (başka klasörde).

## Geçici ve arşiv (okuma, silmeden önce sor)

- `docx_dump2.txt`, `excel_audit_dump.txt`, `final_check.txt`, `schedule_check.txt`, `slides_dump.txt`: ağustos 2026 analiz çıktıları, tek seferlik.
- `dashboard_mockup.html`, `laptop-karsilastirma.html`, `kisisel-marka-dashboard.html`: eski taslak veya kopyalar. Güncel hali ilgili canlı artifact'tadır.
- `2025_mayis_bordro.jpeg`, `2025_haziran_bordro.jpeg`: kişisel veri içerir, git'e eklenmemeli (şu an takipsiz, `.gitignore`'a eklenmesi önerilir).
- `kart_data.txt`: hassas, `.gitignore`'da.
