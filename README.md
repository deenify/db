# 📚 Islamic DB - Quran, Hadith, Duas, Prayer Times (JSON)

A comprehensive collection of structured JSON files for Islamic content, including:

- 🕋 **Quran**
- 📜 **Hadith**
- 🤲 **Duas**
- 🕰️ **Prayer Times**
- And more...

---

## 📦 Purpose

This repository serves as a central source of **raw, structured Islamic data in JSON format**.  
Ideal for developers, researchers, and API builders who want access to clean, ready-to-use data.

---

## 🌐 Usage

You can use the JSON files directly in your applications or APIs.  

**Example fetch URLs:**

- **Quran metadata:** 
metadata.json
[https://raw.githubusercontent.com/deenify/db/refs/heads/main/quran/metadata.json](https://raw.githubusercontent.com/deenify/db/refs/heads/main/quran/metadata.json)  
- **Quran 114 chapters in Achinese language:** 
array.json 
[https://raw.githubusercontent.com/deenify/db/refs/heads/main/quran/edition/Achinese/array.json](https://raw.githubusercontent.com/deenify/db/refs/heads/main/quran/edition/Achinese/array.json)  

---

## 📁 Repository Structure

### Quran

| Path                                | Description                              |
|------------------------------------|------------------------------------------|
| `/quran/metadata.json`             | Quran metadata                            |
| `/quran/edition/English/array.json`| Quran all chapters in English             |
| `/quran/edition/Arabic/array.json` | Quran all chapters in Arabic              |
| `/quran/edition/English/array_la.json`  | Quran chapters in Arabic (Latin script)|
| `/quran/edition/English/array_lad.json` | Latin script with diacritical marks     |

### Hadith

| Path              | Description             |
|------------------|-------------------------|
| `/hadith/metadata.json` | Hadith books metadata |
| `/hadith/abudawud/english.json` |  Abudawud Hadiths collection |

*(Other folders for Duas, Prayer Times, etc., follow the same structure.)*

---

## ⚖️ License

This project is **open-source** and free to use under the [MIT License](LICENSE).

---

> **Note:** This repository does **not** include any API server.  
> It provides only static JSON files for developers and researchers.


**Already using this DB via API:** [Deenify API](https://deenifyapi.vercel.app) as https://deenifyapi.vercel.app
