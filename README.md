# 📄 Relevé Extractor - OCR + Llama4 + Hugging Face API

Ce projet Streamlit permet d'extraire automatiquement les **transactions bancaires** à partir d’un **relevé scanné au format PDF**, en utilisant un modèle **LLaMA 4 hébergé sur Hugging Face**.

<img width="862" alt="Capture Interface streamlit 1" src="https://github.com/user-attachments/assets/deb603db-607c-4075-8e6d-2247a21d8b1f" />


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

<img width="350" alt="Capture Interface streamlit 3" src="https://github.com/user-attachments/assets/64296e7e-f3f5-436c-81f8-90149610dccf" />


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
