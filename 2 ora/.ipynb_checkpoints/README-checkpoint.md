# Adattudomány – 2. óra (Vizualizáció + Diabetes)

Ez a repó az **Adattudomány** kurzus második órájának két Jupyter notebookját tartalmazza:
- **Adatvizualizáció** (gyors áttekintés, beolvasás, matplitlib és seaborn vizualizációk)
- **Diabetes feladatsor** (adatbetöltés OpenML-ről, hiányzó adatok, csoportosítás, korreláció, vizualizáció)

> **Megjegyzés:** A notebookok Binderrel azonnal futtathatók böngészőből – helyi telepítés nélkül.

---

## 👟 Gyors indítás Binderrel


### 1) Adatvizulaizáció notebook
[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/korosig/DataScience/HEAD?labpath=2%20ora/2%20ora%20-%20Adatvizualizacio.ipynb)

### 2) Feladatok (Diabetes) notebook
[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/korosig/DataScience/HEAD?labpath=2%20ora/2%20ora%20-%20Feladatok.ipynb)

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