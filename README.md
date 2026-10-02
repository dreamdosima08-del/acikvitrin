# Açık Vitrin

Küçük işletmeler (astrolog, koç, kuaför, kafe, yerel esnaf) için web sitesi hizmetinin tanıtım sayfası: https://acikvitrin.com/

Statik site, derleme gerektirmez (GitHub Pages).

| Dosya | Görevi |
|---|---|
| `index.html` | Sayfanın kendisi (CSS ve JS içinde) + JSON-LD (ProfessionalService, Offer, FAQPage) |
| `robots.txt` | Arama ve yapay zeka botlarına izin, sitemap bağlantısı |
| `sitemap.xml` | Google için site haritası |
| `llms.txt` | Yapay zeka asistanları için hizmetin düz metin özeti |
| `og-image.png` | Paylaşım görseli (1200x630) |
| `favicon.svg`, `404.html` | Sekme ikonu ve 404 sayfası |

Fiyat veya paket değişirse üç yeri birlikte güncelleyin: `index.html` (görünen metin + JSON-LD) ve `llms.txt`.
