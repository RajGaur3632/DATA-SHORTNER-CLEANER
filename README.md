# 📊 Data Shortner and Data Cleaner

An interactive **Google Colab notebook** for cleaning and shortening company names into easy-to-use abbreviations, acronyms, or friendly short forms.  
This tool is useful for **lead enrichment, CRM cleaning, email personalization, and data preprocessing**.

---

## 🚀 Features
- Input company names via a **textbox** (no hardcoding).
- Choose from three styles:
  - **friendly** → readable short forms (e.g., `FoodBankSJ`)
  - **acronym** → pure acronyms (e.g., `FBSJ`)
  - **initials** → just first letters (e.g., `FBOSJ`)
- Removes common suffixes (`Inc`, `LLC`, `Corp`, etc.).
- Auto-deduplication of duplicates (`XYZ`, `XYZ_2`, …).
- Results displayed directly as a Pandas DataFrame (no CSV export required).
- 100% Google Colab friendly.

---

## 📦 Installation

Open the notebook in [Google Colab](https://colab.research.google.com/) and run the first cell:

```bash
!pip install pandas unidecode ipywidgets
