# obdTalk

- Depo: `C:/source/obdtalk.com` (GitHub: Nitro-Mekatronik/obdtalk.com)
- Teknoloji: nopCommerce tabanlı ASP.NET Core e-ticaret (`Obdtalk.com.sln`, `Presentation/Nop.Web`), Docker ile Coolify'a dağıtım (`Dockerfile`, `deploy/`). Yardımcı Python betikleri `scripts/` altında (`requirements.txt`: pyodbc, psycopg2).
- Pod: OBDTALK (`emails` anahtarı).
- Amaç: obdtalk.com araç arıza tespit ve OBD ürünleri sitesi. Staging `up.obdtalk.com`, üretim `obdtalk.com`.

## Notlar
- Windows → Docker (Coolify) geçiş planı depoda `plan.md` içinde; göreve başlamadan oku.
- `icerik/` klasöründe site içerikleri ve blog taslakları durur.
- Büyük .NET derlemesi uzun sürer; küçük değişikliklerde yalnızca ilgili projeyi derle.
