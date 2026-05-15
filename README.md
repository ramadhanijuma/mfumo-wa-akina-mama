# 📚 Mfumo wa Madrasa | Madrasa Management System

Mfumo kamili wa kusimamia shule ya Qur'ani (Madrasa) unaojumuisha:

- Usajili na usimamizi wa wanafunzi
- Kuingiza na kuona matokeo ya masomo
- Usimamizi wa walimu
- Ratiba ya wiki
- Rekodi za malipo ya ada
- Mfumo wa login kwa watumiaji

Mfumo umetengenezwa kwa kutumia:

- Google Apps Script
- Google Sheets
- HTML / CSS / JavaScript

---

# ✅ Vipengele vya Mfumo

| Moduli | Maelezo |
|--------|----------|
| Wanafunzi | Ongeza, hariri na orodhesha wanafunzi |
| Matokeo | Ingiza alama za Qur'an, Tajwiid, Hadithi, Fiqhi na Kiarabu |
| Walimu | Usimamizi wa walimu na masomo yao |
| Ratiba | Ratiba ya vipindi vya kila wiki |
| Malipo | Rekodi malipo ya ada |
| Login | Mfumo wa kuingia kwa username na password |

---

# 🛠️ Teknolojia Zinazotumika

- Google Apps Script (Backend API)
- Google Sheets (Database)
- HTML / CSS / JavaScript (Frontend)
- Font Awesome
- Google Fonts

---

# 🚀 Mwongozo wa Kuanzisha Mfumo

## 1. Unda Google Spreadsheet

Unda spreadsheet mpya kwenye Google Drive.

Tumia Spreadsheet hii:

```javascript
const SPREADSHEET_ID = '1QL4TQ7teCj9r6a_RkmwZC0PNcSZCOgOrMoAq-H3Ml3Q';
```

---

## 2. Unda Google Apps Script Project

Nenda kwenye:

```text
https://script.google.com
```

Kisha:

- Unda project mpya
- Weka faili mbili:

### `Code.gs`

```javascript
// Bandika Apps Script code hapa
```

### `index.html`

```html
<!-- Bandika HTML code hapa -->
```

---

# 🌐 Web App URL

```javascript
const WEB_APP_URL = 'https://script.google.com/macros/s/AKfycbxBj2oyrtZBchTri1QnJpVVqrL3r0lC0_6-0UFBeBqOz6Suv-f_yOxV25eT_mFktS4/exec';
```

---

# 📤 Deployment

Bofya:

```text
Deploy → New deployment → Web app
```

Kisha chagua:

| Setting | Value |
|----------|--------|
| Execute as | Me |
| Who has access | Anyone |

Baada ya hapo:

- Bofya `Deploy`
- Nakili URL ya Web App

---

# 👤 Login ya Mwanzo

```text
Username: admin
Password: admin123
```

---

# 📁 Muundo wa Google Sheets

| Sheet Name | Maelezo |
|------------|----------|
| Users | Username na Password |
| Wanafunzi | Taarifa za wanafunzi |
| Walimu | Taarifa za walimu |
| Matokeo | Alama za wanafunzi |
| Ratiba | Ratiba ya vipindi |
| Malipo | Rekodi za malipo |

---

# 📚 Masomo Yanayotumika

- Qur'an
- Tajwiid
- Hadithi
- Fiqhi
- Lugha ya Kiarabu

---

# 🎓 Mfumo wa Madaraja

| Alama | Daraja |
|--------|---------|
| 45 – 50 | A |
| 40 – 44 | B |
| 35 – 39 | C |
| 30 – 34 | D |
| Chini ya 30 | F |

---

# 🔧 Customization

## Kubadilisha Ada

Tafuta:

```html
value="5000"
```

Kisha badilisha kiasi unachotaka.

---

## Kubadilisha Masomo

Tafuta:

```html
<select id="resultSubject">
```

Ongeza au punguza masomo.

---

## Kubadilisha Ratiba

Ratiba ipo kwenye sehemu ya:

```javascript
Ratiba
```

Unaweza kuongeza siku au vipindi.

---

# 🐛 Troubleshooting

| Tatizo | Suluhisho |
|--------|------------|
| Login haifanyi kazi | Hakikisha sheet ya `Users` ipo |
| Data haionekani | Angalia headers za Google Sheet |
| CORS Error | Tumia Web App URL moja kwa moja |
| Spreadsheet haifunguki | Authorize script kwanza |

---

# 📄 Leseni

Mfumo huu unaweza kutumiwa bure kwa madrasa na taasisi za elimu ya Kiislamu.

Unaweza kuubadilisha kulingana na mahitaji yako.

---

# 🙏 Shukrani

Imetengenezwa kwa kutumia:

- Google Apps Script
- Google Sheets
- HTML / CSS / JavaScript

Kwa matumizi ya madrasa, masjid na taasisi za elimu ya Kiislamu.

---
