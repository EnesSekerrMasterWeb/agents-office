# Nitro Bilişim — Beyin

Bu klasör ofisin ortak hafızasıdır. Ajanlar her görevden önce buradaki notları okur; bitirdikleri işi `Agents Office/` altına tarihli not olarak yazar.

## Şirket
- Nitro Bilişim: web siteleri geliştiren ve yöneten bir bilişim şirketi.
- Birden fazla site var; ofiste her pod bir siteye karşılık gelir.
- Sitelerin depoları `C:/Users/Efekan/source/<site>` altında durur ve `office.config.local.json` içindeki `departments.<pod>.repo` ile poda bağlanır.

## Çalışma kuralları
- Her şey Türkçe yazılır: görev başlıkları, raporlar, commit mesajı önerileri.
- Kod değişiklikleri depo içinde yapılır; commit ve push sahibine bırakılır.
- Sahibi onaylamadan dışarıya hiçbir şey gönderilmez.

## Siteler
- [[obdtalk]] — obdTalk, nopCommerce (ASP.NET Core); pod OBDTALK.
- [[nitrobilisim-store]] — Nitro Store, Smartstore 6.3 (ASP.NET Core + PostgreSQL); pod NİTRO STORE.
