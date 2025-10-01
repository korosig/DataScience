# Szövegbányászat/Natural Language Processing, NLP – 3. óra 
Ez a repó az **Adattudomány** kurzus második órájának két Jupyter notebookját tartalmazza:
- **Szövegbányászat/Natural Language Processing, NLP** (hiányzó adatok, tokenizálás, korreláció, vektorizáció)
- **Twitter-Sentiment-Analysis** (hiányzó adatok, tokenizálás, korreláció, vektorizáció)

> **Megjegyzés:** A notebookok Binderrel azonnal futtathatók böngészőből – helyi telepítés nélkül.

---

## 👟 Gyors indítás Binderrel vagy GithubCodeSpaces


### 1) Szövegbányászat/Natural Language Processing, NLP notebook
[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/korosig/DataScience/HEAD?labpath=3%20ora%20-%20Szovegbanyaszat/3%20ora%20-%20Szovegbanyaszat.ipynb)

### 2) Feladatok (Sentiment) notebook
[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/korosig/DataScience/HEAD?labpath=3%20ora%20-%20Szovegbanyaszat/3%20ora%20-%20Feladatok.ipynb)

### 3) GithubCodeSpaces
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/korosig/DataScience)

## 💾 Fontos: mentés és perzisztencia Binderben

- A Binder **ideiglenes környezet** – a változtatásaid **nem íródnak vissza** a GitHub repóba.
- **Inaktivitás** esetén a szerver **kb. 10 perc** után leállhat; ilyenkor a nem letöltött módosítások elvesznek.
- Az egyes futtatásokra **idő- és erőforrás-korlátok** vonatkoznak (lásd a következő szakaszt).

### Hogyan mentsd el a munkádat?
- **JupyterLab-ben**: jobb klikk a notebookon → **Download** *(vagy File → Save and Export Notebook As → Notebook (.ipynb))*.
- **Classic nézetben**: *File → Download as → Notebook (.ipynb)*.
- **Verziókezeléshez**: dolgozz helyben, és **commit/push** a GitHub repóba; Binder újraindításkor a repó HEAD állapotát tölti be.

> Tipp: nagyobb feladat előtt készíts **gyakori letöltéseket** (lokális mentések), különösen, ha hosszabban nem futtatsz sejtet.

---

## 🧱 Binder korlátok (gyakorlati összefoglaló)

- **Erőforrások**: tipikusan **1 CPU** és **korlátozott RAM** (néhány GB nagyságrend). Nagy számítások/ML tréning **megállhatnak vagy kiléphetnek** memóriahiánnyal.
- **Idő**: inaktív munkamenet ~**10 perc** után leállhat; hosszú futásoknál tartsd „életben” a kernelt (időnként futtass cellát).
- **Perzisztencia**: a környezet **nem tartós** – installált csomagok és generált fájlok a munkamenet végén elvesznek.
- **Hálózat**: külső letöltések működhetnek, de **lassabbak/korlátozottak** lehetnek (rate‑limit, tűzfal). Az OpenML lekérések időnként throttlingot kaphatnak.
- **GPU/TPU**: **nem elérhető** mybinder.org-on.



---