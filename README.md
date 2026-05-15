# 📚 Mfumo wa Madrasa | Madrasa Management System

Mfumo kamili wa kusimamia shule ya Qur'ani (Madrasa) unaojumuisha:
- Usajili na usimamizi wa wanafunzi.
- Kuingiza na kuona matokeo ya masomo (Qur'an, Tajwiid, Hadithi, Fiqhi, Lugha ya Kiarabu) – alama 50 na madaraja.
- Usimamizi wa walimu na ugawaji wa masomo.
- Ratiba ya wiki (Jumamosi – Jumatano, vipindi 2 kwa siku).
- Kurekodi malipo ya ada (Tsh 5,000/= kwa mwezi).
- Uthibitishaji wa watumiaji (login).

Mfumo unatumia **Google Apps Script** kwa back-end na **Google Sheets** kwa uhifadhi wa data. Unaweza kuupeleka kwenye **GitHub Pages** au kutumia URL ya web app moja kwa moja.

---

## ✅ Vipengele (Features)

| Moduli | Maelezo |
|--------|----------|
| Wanafunzi | Ongeza, orodhesha wanafunzi (jina, darasa, mzazi, simu, anwani) |
| Matokeo | Ingiza alama (0-50) kwa kila somo; daraja (A–F) linakokotolewa kiotomatiki |
| Walimu | Ongeza na orodhesha walimu wanaofundisha |
| Ratiba | Weka ratiba ya siku kwa vipindi viwili (saa 8–10) Jumamosi hadi Jumatano |
| Malipo | Rekodi malipo ya Tsh 5,000 kwa mwezi na uone historia |
| Login | Watumiaji wanaoingia kwa jina la mtumiaji na nenosiri (default: admin / admin123) |

---

## 🛠️ Teknolojia Zinazotumika

- **Google Apps Script** (Back-end API & Hosting)
- **Google Sheets** (Database)
- **HTML/CSS/JS** (Front-end)
- **Font Awesome / Google Fonts** (Optional)

---

## 🚀 Mwongozo wa Kuanzisha (Deployment)

### 1. Unda Google Sheet
- Unda spreadsheet mpya (au tumia iliyopo) kwenye Google Drive.
- Nakili **ID** ya spreadsheet (kutoka kwenye URL: `.../d/SPREADSHEET_ID/edit...`).

### 2. Unda Mradi wa Google Apps Script
- Nenda kwenye [script.google.com](https://script.google.com) na uanze mradi mpya.
- Katika mhariri, unda faili mbili:

#### `Code.gs`
```javascript
// Nakili msimbo kamili wa Apps Script (uliopewa hapo juu) hapa
// Kumbuka: Kubadilisha SPREADSHEET_ID kuwa yako
index.html
html
<!-- Nakili HTML kamili ya mfumo (iliyopewa hapo juu) hapa -->
3. Sanidi Mipangilio ya Deployment
Bofya Deploy → New deployment → Web app.

Execute as: Me (mwenyewe)

Who has access: Anyone (si "Anyone with link", chagua "Anyone")

Bofya Deploy na nakili URL ya web app (k.m. https://script.google.com/macros/s/.../exec).

4. Ongeza Watumiaji (Users)
Google Sheet yako itakuwa na karatasi inayoitwa Users.

Ikiwa haipo, itaundwa kiotomatiki.

Weka safu ya kwanza: username, password

Kisha weka mstari wa kwanza wa mtumiaji: admin, admin123

Unaweza kuongeza watumiaji wengine.

5. Tumia Mfumo
Fungua URL ya web app uliyopata.

Ingia kwa admin / admin123.

Anza kusajili wanafunzi, walimu, ratiba, matokeo na malipo.

Kumbuka: Ikiwa unataka kutumia mfumo kwenye GitHub Pages, nakili HTML kamili (iliyojitegemea) kwenye index.html ya repo yako na ubadilishe SCRIPT_URL kuwa URL ya web app ya Google Apps Script. Lakini njia rahisi ni kutumia URL ya web app moja kwa moja (hakuna CORS, kwa sababu mfumo unahudumiwa na Google).

📁 Muundo wa Google Sheets
Karatasi zifuatazo zinaundwa moja kwa moja (au weka mwenyewe):

Jina la Karatasi	Maelezo
Users	Watumiaji (username, password)
Wanafunzi	id, jina, darasa, mzazi, simu, anwani, tarehe, status
Walimu	id, jina, simu, somo
Matokeo	uid, student_id, jina, darasa, somo, alama, daraja, mwaka, mwezi
Ratiba	siku, kipindi1, kipindi2, mwalimu1, mwalimu2
Malipo	id, student_id, jina, kiasi, mwezi, mwaka, tarehe
🔧 Marekebisho (Customization)
Badilisha Ada – Kwenye HTML, tafuta value="5000" na ubadilishe.

Masomo – Orodha ya masomo iko kwenye <select id="resultSubject"> pamoja na chaguo.

Siku za Ratiba – Zimeorodheshwa kwa mwongozo; unaweza kuongeza au kupunguza.

Alama na Daraja – Kanuni: A (45-50), B (40-44), C (35-39), D (30-34), F (<30). Iko kwenye backend (saveResult).

🐛 Utatuzi wa Makosa (Troubleshooting)
Tatizo	Suluhisho
Login haifanyi kazi	Hakikisha karatasi ya Users ipo na ina mtumiaji admin / admin123.
CORS error (wakati wa kupeleka HTML kwenye GitHub Pages)	Badala yake, tumia URL ya web app moja kwa moja (inayotolewa na Google Apps Script). Mfumo ulio ndani ya script hauna CORS.
Data haionyeshwi	Angalia kama karatasi zina headers sahihi. Ikiwa bado, fungua console (F12) uone kama kuna makosa.
Google Sheet haijafunguliwa	Hakikisha umeidhinisha (authorize) script mara ya kwanza.
📄 Leseni
Mfumo huu ni wa kutumia bure kwa madrasa na shule za Qur'ani. Unaweza kurekebisha kwa matakwa yako.

🙏 Shukrani
Imetengenezwa kwa kutumia Google Apps Script, HTML, na Google Sheets. Inaendeshwa kwa ushirikiano na Masjid Taqwa na wadau wa elimu ya Kiislamu.

text

Unaweza kubandika hii kwenye faili ya `README.md` kwenye GitHub repo yako. Ikiwa unataka nirekebishe au niongeze sehemu fulani (k.m. picha, maelezo ya utatuzi zaidi), niko tayari.
