# Adattudomány – 1. óra (Pandas + Titanic)

Ez a repó az **Adattudomány** kurzus első órájának két Jupyter notebookját tartalmazza:
- **Python/Pandas alapok** (gyors áttekintés, beolvasás, alapszűrés, statisztika)
- **Titanic feladatsor** (adatbetöltés OpenML-ről, hiányzó adatok, csoportosítás, korreláció, vizualizáció)

> **Megjegyzés:** A notebookok Binderrel azonnal futtathatók böngészőből – helyi telepítés nélkül.

---

## 👟 Gyors indítás Binderrel vagy GithubCodeSpaces


### 1) Python Intro notebook
[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/korosig/DataScience/HEAD?labpath=1%20ora%20-%20DataFrame/1%20ora%20-%20DataFrame/1%20ora%20-%20Python%20Programoz%C3%A1s%20Alapok.ipynb)

### 2) DataFrame notebook
[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/korosig/DataScience/HEAD?labpath=1%20ora%20-%20DataFrame/1%20ora%20-%20DataFrame/1%20ora%20-%20DataFrame.ipynb)

### 3) Feladatok (Titanic) notebook
[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/korosig/DataScience/HEAD?labpath=1%20ora%20-%20DataFrame/1%20ora%20-%20Feladatok.ipynb)

### 4) GithubCodeSpaces
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
