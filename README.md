# calving97-ux
Data Science | ESG Analytics | FinBERT
### 👋 Hi, I’m Chenguang (Calvin) Wang
![Python](https://img.shields.io/badge/Python-3.10-blue) ![FinBERT](https://img.shields.io/badge/FinBERT-ESG-green)
I’m a data-driven researcher focused on **sustainability accounting**, **ESG narrative analysis**, and **computational social science**.

🔍 My current research asks:  
*Do Swedish energy firms use carbon disclosure as a genuine governance tool, or merely as a legitimation device to manage external perceptions?*

📊 I apply **FinBERT** (a financial BERT model) to annual reports and press releases (2015–2025) of ~50–60 Swedish energy producers – including Vattenfall, E.ON, Stockholm Exergi – to quantify:

- **Green framing density** (positive/negative/neutral sentiment per sentence)
- **Carbon impression management tactics** (scope exclusions, baseline shifts, offset framing)

📈 I combine this textual analysis with:
- Verified emissions data from the Swedish EPA (Naturvårdsverket)
- A **continuous difference-in-differences** design (2015 Swedish Energy Agreement as a quasi-natural experiment)
- **Spatial econometrics** (Moran’s I, spatial Durbin models) to capture regional institutional spillovers
- **Ownership structure** (municipal, family, public) as a key moderator

🎯 I aim to bridge **legitimacy theory**, **information regimes**, and **regional science** – showing how local monitoring capacity shapes corporate green talk.

📁 This repo contains the FinBERT pipeline I built:  
`PDF → sentence extraction → FinBERT inference → sentiment scores → CSV export`  
Ready for replication or adaptation to other ESG datasets.

---

📫 Reach me: [calving97-ux](https://github.com/calving97-ux)  
📄 Full research proposal available upon request.
