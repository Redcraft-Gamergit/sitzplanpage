# Sitzplan Pages

Dieses Paket ist das sichtbare Frontend. Lade seinen gesamten Inhalt als **Cloudflare Pages**-Projekt hoch.

1. Im Cloudflare-Dashboard: **Workers & Pages** → **Create** → **Upload your static files**.
2. Den Inhalt dieses Ordners oder die Datei `sitzplan-pages-upload.zip` hochladen.
3. Nach der Worker-Veröffentlichung die Worker-URL in `config.js` eintragen und Pages erneut hochladen.

Die Seite funktioniert direkt nach dem Upload auch ohne Worker mit lokaler Browser-Speicherung. Der Worker ist der sichere Ausbau für API, D1 und öffentliche Planlinks.
