# Enron-Spam-Data-Preprocessing-Script-by-Fabian-Jirges
Enron Spam Data Preprocessing Script for Comparative Analysis of Classical and Contextual Models for Spam Detection: Naive Bayes vs. BERT

Dieses Skript liest rohe E-Mail-Textdateien aus zwei Ordnern („ham“ und „spam“), bereinigt sie von irrelevanten Metadaten und Steuerzeichen und speichert das Ergebnis in einer Excel-Datei. Zusätzlich wird jedem Eintrag ein numerisches Label (`0` für Ham, `1` für Spam) hinzugefügt.

---

## Inhaltsverzeichnis

1. [Voraussetzungen](#voraussetzungen)  
2. [Installation](#installation)  
3. [Verwendung](#verwendung)  


---

## Voraussetzungen

- Python 3.7+  
- Bibliotheken:
  - `pandas`  
  - (optional) `openpyxl` oder `xlsxwriter` für Excel-Ausgabe  

## Installation
```bash
pip install pandas openpyxl

## Verwendung
enron_datensätze

## Beispiel
ham_folder  = r'C:\Daten\Enron_xx\ham'
spam_folder = r'C:\Daten\Enron_xx\spam'
excel_path  = r'C:\Daten\Enron\enron_cleaned.xlsx'
