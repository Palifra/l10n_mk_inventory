# Macedonian Translations for Odoo 18 Inventory Module
# Македонски преводи за Odoo 18 Inventory модул

[![License: LGPL-3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![Odoo Version](https://img.shields.io/badge/Odoo-18.0-875A7B.svg)](https://www.odoo.com/)
[![Language](https://img.shields.io/badge/Language-Macedonian-red.svg)](https://en.wikipedia.org/wiki/Macedonian_language)

## 📋 Overview / Преглед

This module provides **Macedonian (mk_MK)** translations for the Odoo 18 Inventory/Stock module.

Овој модул обезбедува **македонски (mk_MK)** преводи за Odoo 18 Inventory/Stock модулот.

## 📊 Translation Statistics / Статистика на преводот

- **Total entries:** 1,754
- **Translated:** 1,688 (96.2%)
- **Quality:** 100% (all placeholders and HTML preserved)
- **Characters:** 465,000+

### Coverage / Покриеност

- ✅ Warehouse / Магацин
- ✅ Location / Локација
- ✅ Transfer / Трансфер
- ✅ Operations / Операции
- ✅ Product / Производ
- ✅ Lot / Serial Number / Лот / Сериски број
- ✅ Picking / Picking налог
- ✅ Move / Движење
- ✅ Stock / Залиха

## 🚀 Installation / Инсталација

### Method 1: Manual Installation

1. Download this module:
```bash
cd /path/to/odoo/addons
git clone https://github.com/Palifra/l10n_mk_inventory.git
```

2. Restart Odoo:
```bash
sudo systemctl restart odoo
# or
docker-compose restart odoo
```

3. Install the module:
   - Go to **Apps**
   - Remove the **Apps** filter
   - Search for **"North Macedonia - Inventory"**
   - Click **Install**

4. Activate Macedonian language:
   - Go to **Settings → Users → Preferences**
   - Select **Language → Macedonian / македонски јазик**
   - Click **Save**
   - Refresh the page (F5)

### Method 2: Docker

Add to your `docker-compose.yml`:
```yaml
volumes:
  - ./l10n_mk_inventory:/mnt/extra-addons/l10n_mk_inventory
```

## 📦 Dependencies / Зависности

- `stock` (Odoo Inventory/Stock module)

## 🔧 Technical Details / Технички детали

### Module Structure / Структура на модулот

```
l10n_mk_inventory/
├── __init__.py
├── __manifest__.py
├── i18n/
│   └── mk_MK.po          # 1,688 translated terms
└── README.md
```

### Translation Quality / Квалитет на преводот

- ✅ **0 placeholder errors** - All `%(variable)s` placeholders preserved
- ✅ **0 HTML errors** - All HTML tags and attributes preserved
- ✅ **100% accuracy** - Verified with automated quality scanner

### Key Terminology / Клучна терминологија

| English | Македонски |
|---------|-----------|
| Inventory | Магацин |
| Warehouse | Магацин |
| Stock | Залиха |
| Transfer | Трансфер |
| Location | Локација |
| Operation | Операција |
| Product | Производ |
| Lot | Лот |
| Serial Number | Сериски број |
| Picking | Picking налог |
| Delivery | Испорака |
| Receipt | Примање |

## 🌍 About Macedonian Language / За македонскиот јазик

Macedonian (македонски јазик) is a South Slavic language spoken primarily in North Macedonia. This translation follows official terminology used in business and accounting contexts.

Македонскиот јазик е јужнословенски јазик што се зборува главно во Северна Македонија. Овој превод ја следи официјалната терминологија што се користи во деловен и сметководствен контекст.

## 🤝 Contributing / Придонес

Contributions are welcome! If you find translation errors or have suggestions:

1. Open an issue on GitHub
2. Submit a pull request
3. Contact: info@eskon.com.mk

## 📄 License / Лиценца

This module is licensed under **LGPL-3.0** - same as Odoo.

## 👥 Credits / Заслуги

**Author / Автор:** ЕСКОН-ИНЖЕНЕРИНГ ДООЕЛ Струмица

**Translation Method / Метод на превод:**
- DeepL API (Beta Macedonian language)
- Manual quality control and corrections
- Automated placeholder/HTML preservation

**Tools Used / Користени алатки:**
- DeepL API for translation
- polib for PO file manipulation
- Custom quality scanner for validation

## 📧 Contact / Контакт

- **Organization:** ЕСКОН-ИНЖЕНЕРИНГ ДООЕЛ Струмица
- **Email:** info@eskon.com.mk
- **Website:** https://www.eskon.com.mk
- **GitHub:** https://github.com/Palifra

## 🔗 Related Modules / Поврзани модули

- [l10n_mk_invoicing](https://github.com/Palifra/l10n_mk_invoicing) - Invoicing/Accounting translations
- [l10n_mk](https://github.com/Palifra/l10n_mk) - Chart of Accounts for North Macedonia

---

**Supported Odoo Version:** 18.0
**Language:** Macedonian (mk_MK)
**Last Updated:** 2025-11-15

**Среќно со македонскиот Odoo! 🇲🇰**
