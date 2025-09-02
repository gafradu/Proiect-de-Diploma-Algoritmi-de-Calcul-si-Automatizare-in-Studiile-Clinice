# 📘 Proiect de Diplomă – Algoritmi de Calcul și Automatizare în Studiile Clinice

Acest depozit GitHub conține codul sursă, seturile de date și rezultatele aferente proiectului de diplomă intitulat:  
**„Algoritmi de Calcul și Automatizare în Studiile Clinice”**  

## 📂 Structura

```
/Cod
    Cod_Algoritm.ipynb     → Codul complet al algoritmului (Python, Google Colab)

/SetDeDate_RezultateAlgoritm
    /Scenariul 1                     → Date inițiale și rezultate (strategii fereastră min/max)
    /Scenariul 2                     → Date și rezultate fără aplicarea regulilor DND/DNC
    /Scenariul 3                     → Rulări succesive pe termen lung (zilele 0, 7, 14, 21, 28, 55, 56, 83, 84)

/ModeleDeBaza
    SetDeDate_ModelDeBaza.xlsx       → Modelul de bază al setului de date utilizat pentru simulări
```

---

## ⚙️ Tehnologii utilizate  

- **Python 3**  
- **Google Colaboratory** (execuție în cloud)  
- Biblioteci Python:  
  - `pandas` – manipulare seturi de date  
  - `numpy` – calcule numerice  
  - `openpyxl` – lucrul cu fișiere Excel  

---

## ▶️ Cum se rulează algoritmul  

1. Clonează repo-ul local:  
   ```bash
   git clone https://github.com/gafradu/Proiect-de-Diploma-Algoritmi-de-Calcul-si-Automatizare-in-Studiile-Clinice.git
   cd Proiect-de-Diploma-Algoritmi-de-Calcul-si-Automatizare-in-Studiile-Clinice
   ```

2. Deschide fișierul **`/Cod/Algoritm_StudiuClinic.ipynb`** în Google Colab.  
   - Alternativ, îl poți încărca și rula local folosind Jupyter Notebook.  

3. Încarcă seturile de date dorite din folderul **`/SetDeDate_RezultateAlgoritm`**, sau creeaza unul pornind de la **`/ModeleDeBaza/SetDeDate_ModelDeBaza.xlsx`**.

4. Update la urmatoarele valori din cod: **`fileName`** si **`fileFolderPath`**.

---

## 📊 Conținutul seturilor de date  

- **SetariGenerale** – data de referință pentru execuția algoritmului.  
- **Depozite** – informații despre depozite și conexiunile lor către clinici.  
- **Clinici** – clinici active/inactive și strategiile lor de aprovizionare.  
- **Strategii** – ferestre minime și maxime pentru reaprovizionare.  
- **StrategiiMedicamente** – valori tampon pentru fiecare medicament.  
- **Vizite** – structura vizitelor pacientului.  
- **Dispensari** – cantitățile standard de medicamente per tratament și vizită.  
- **Medicamente** – parametrii DND și DNC pentru calculul expirării.  
- **Pacienti / PacientiVizite** – date despre pacienți și vizitele lor.  
- **Loturi** – date despre loturi și expirare.  
- **InventarDepozite / InventarClinici** – inventarul curent la depozite și clinici.  

---

## 🔗 Referințe  

Acest repo este menționat în teza de diplomă (vezi **Anexa C**), Universitatea Națională de Știință și Tehnologie „Politehnica București”, Facultatea de Inginerie Medicală, 2025.  
