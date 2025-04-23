# 📄 Relevé Extractor - OCR + Llama4 + Hugging Face API

Ce projet Streamlit permet d'extraire automatiquement les **transactions bancaires** à partir d’un **relevé scanné au format PDF**, en utilisant un modèle **LLaMA 4 hébergé sur Hugging Face**.

## 🚀 Fonctionnalités

- 📤 Upload d’un fichier PDF contenant des relevés bancaires scannés  
- 🧠 Analyse des images via un modèle LLM (Hugging Face API)  
- 🧾 Extraction structurée des transactions :
  - Date Opération
  - Date Valeur
  - Libellé
  - Débit
  - Crédit
- 📊 Affichage dans un tableau Streamlit
- 📥 Export en **fichier Excel (.xlsx)**

---

## 🧪 Exemple d'utilisation

1. Lancer l'application :
```bash
streamlit run app.py
```
2. Saisir votre clé API Hugging Face

3. Uploader un fichier PDF

4. Télécharger le tableau des transactions extraites en Excel

## 👨‍💻 Auteur
- Développé par Naya Oussama
- 💬 Contact : oussamanaya8@gmail.com
