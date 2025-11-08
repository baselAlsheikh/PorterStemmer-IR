# 🧩 Porter Stemmer – Information Retrieval Project

This project implements the **Porter Stemming Algorithm** in Python, as part of an Information Retrieval assignment.

The Porter Stemmer reduces English words to their **root form** (stem) using a series of suffix-removal rules — for example:  
`caresses → caress`, `ponies → poni`, `relational → relate`.

---

## 📘 Project Description

- Implements the main steps of **Porter’s algorithm** (as described in the course slides):
  1. Remove plural and simple suffixes (`sses → ss`, `ies → i`, `s → ""`)
  2. Remove past/continuous endings (`ed`, `ing`)
  3. Normalize morphological endings (`ational → ate`, `tional → tion`, etc.)
  4. Apply conditional rule `(m>1) ement →` (e.g., `replacement → replac`, `cement → cement`)
- Includes examples and printed output for verification.

---

## 🧠 How to Run

1. Open the notebook:
   - **Option 1:** On GitHub → open `PorterStemmer.ipynb` → click “Open in Colab” (if available)
   - **Option 2:** Download the notebook and open it locally in **Jupyter Notebook** or **JupyterLab**

2. Run all cells to see:
   - The algorithm implementation  
   - Example outputs for various English words

---

## 📊 Example Output

| Original | Stemmed |
|-----------|----------|
| caresses | caress |
| ponies | poni |
| relational | relate |
| replacement | replac |
| cement | cement |

---

## 👤 Author
**Basel Alsheikh**  
Information Retrieval Project – Porter Stemmer Implementation  
📅 November 2025
