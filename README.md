# Bulgarian-AI-ORC-LOCAL-and-FAST-NO-INTERNET-NEEDED
Преносим инсталатор за локален български AI (BgGPT Gemma-3-4B-IT на INSAIT) без Python, без администраторски права и без облак. Portable, zero-Python, zero-Admin Windows 10/11 installer for local Bulgarian AI (INSAIT BgGPT Gemma-3-4B-IT) with optional Hybrid OCR, Vision, and Scanned PDF Book support


## 🇧🇬 Финално издание v12 (100% офлайн след инсталация)

Два тествани, преносими Windows 10/11 инсталатора без Python и без администраторски права:

| Пакет | Размер | Файлове | Какво включва |
| :--- | :--- | :---: | :--- |
| **`BgGPT-OneClick-v12-Fast-FINAL.zip`** | 20 704 B | 10 | Бърз локален BgGPT (`INSAIT`, 3,18 GB, `-c 4096`), автоматичен CUDA/Vulkan/CPU избор + AnythingLLM Desktop. |
| **`BgGPT-OneClick-v12-OCR-Vision-FINAL.zip`** | 49 923 B | 14 | Бърз BgGPT (`:8081`) + хибриден мост (`:8080`: Windows OCR за текст + `SmolVLM2-2.2B` на поискване за снимки/обекти/графики) + офлайн четец за сканирани PDF книги (`BgGPT Local - OCR`). |

### Включени финални поправки
- Отстранена `.NET GDI+` грешка (`A generic error occurred in GDI+.`) при отваряне на изображения и клипборд в `BgGPT-OCR-GUI.ps1` и `BgGPT-OCR-Bridge.ps1` чрез клониране в `32bpp ARGB`.
- Директно сваляне и SHA-256 верификация на `SmolVLM2-2.2B-Instruct` (`Q4_K_M` + `mmproj Q8_0`) без зависимост от Hugging Face API парсване в PowerShell 5.1.
- 100% ASCII имена на десктоп преките пътища (`BgGPT Local - Start.lnk`, `BgGPT Local - OCR.lnk`) и премахнати Unicode двойни кавички в PowerShell 5.1 скриптовете.

---

## 🇬🇧 v12 Final Release (100% Offline After Setup)

Two validated, portable Windows 10/11 installers with zero Python and zero Admin rights:

- **`BgGPT-OneClick-v12-Fast-FINAL.zip`** — lightweight fast local INSAIT BgGPT (`-c 4096`) with automatic CUDA/Vulkan/CPU runtime selection (including legacy AMD R9 390 flags) and AnythingLLM Desktop integration.
- **`BgGPT-OneClick-v12-OCR-Vision-FINAL.zip`** — full hybrid edition combining fast BgGPT (`:8081`), a local `.NET TcpListener` bridge (`:8080`: native Windows OCR + on-demand `SmolVLM2-2.2B-Instruct`), and a native offline scanned PDF book OCR tool (`Windows.Data.Pdf` + `Windows.Media.Ocr`).

---

## 🔐 SHA-256 Checksums

| Asset | Size | Files | SHA-256 |
| :--- | :---: | :---: | :--- |
| `BgGPT-OneClick-v12-Fast-FINAL.zip` | 20,704 B | 10 | `e5156d1e1ce9a7c3ce2b7b232bd3da3cd08980df6640c0af52a283342283043b` |
| `BgGPT-OneClick-v12-OCR-Vision-FINAL.zip` | 49,923 B | 14 | `ae0c5e065a5f827c7196ca91240c6bb1198176fdd19656a979375b4b319dd7e6` |
