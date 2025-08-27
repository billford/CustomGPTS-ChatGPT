# BillfordX Custom GPT Collection

A curated set of specialized GPTs designed and packaged for repeatable use, version control, and collaboration. Each GPT in this repository is scoped to a specific domain with clear behaviors, policies, and test cases.  

---

## 📚 Table of Contents

- [📸 ShutterMuse](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/shutter-muse) – Photography shot selector & planner  
- [🍷 Saucy Sommelier](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/saucy-sommelier) – Flirty wine & food pairing companion  
- [🛡️ FRACAS](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/fracas) – Firewall expert for rule reviews & compliance  
- [📄 Cybersecurity Tabletop Designer](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/cybersecurity-tabletop-designer) – Cyber training scenario builder  
- [🧩 Cybersecurity Quiz Wizard](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/cybersecurity-quiz-wizard) – Interactive security quiz master  
- [🌱 Future GPTs](#-future-gpts) – Planned or upcoming builds  

---

## 📦 Included GPTs

### [📸 ShutterMuse](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/shutter-muse)  
*A photography shot selector assistant.*  
- Helps photographers choose the right shot type, settings, composition, and mood styling  
- Field-friendly advice across genres (portrait, product, street, landscape)  
- Offers a **guided flow** and **FAQ** for quick planning  
- Scope-locked: only responds to photography topics  

---

### [🍷 Saucy Sommelier](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/saucy-sommelier)  
*A flirty wine & food pairing companion.*  
- Suggests wine for dishes and dishes for wines, with playful, witty banter  
- Highlights flavors, textures, and regional matches  
- Turns up charm for certain users (Courtney & Lisa 😉)  
- Scope-locked: redirects non-culinary questions back to food & wine  

---

### [🛡️ FRACAS](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/fracas)  
*Firewall Rules Analysis, Compliance, And Security.*  
- Reviews firewall configs for accuracy, hardening, and compliance  
- Maps findings to frameworks (PCI DSS, HIPAA, SOC 2, ISO 27001)  
- Rejects non-text or irrelevant uploads firmly  
- Provides exportable reports (PDF or JSON) with **worst-case scenario modeling**  
- Strictly professional tone for IT/security pros  

---

### [📄 Cybersecurity Tabletop Designer](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/cybersecurity-tabletop-designer)  
*A scenario generator for cyber training.*  
- Generates concise tabletop ideas or builds full, detailed exercises  
- Includes objectives, injects, roles, timelines, outcomes, and debrief prompts  
- Provides export option to PDF for facilitation use  
- Covers common threats: ransomware, phishing, insider threats, supply chain  

---

### [🧩 Cybersecurity Quiz Wizard](https://github.com/billford/CustomGPTS-ChatGPT/tree/main/gpts/cybersecurity-quiz-wizard)  
*An interactive cybersecurity quiz master.*  
- Builds multiple-choice quizzes (A–D) across security domains  
- Customizable by difficulty, topic, and number of questions  
- Provides feedback (🎉 Correct / ❌ Incorrect) with concise explanations  
- Tracks scores and provides motivational summaries  

---

## 🌱 Future GPTs

This repository is designed to grow as new GPTs are created and packaged. 

---

## 🏗️ Structure

Each GPT lives in its own directory with the subdirectories:  
- `prompt/` → system instructions, style, examples, FAQ/guided flows  
- `config/` → metadata, limits, policies  
- `knowledge/` → optional uploaded files + sources  
- `actions/` → API schemas (OpenAPI) and usage notes  
- `tests/` → smoke tests, edge cases, evaluation rubric  
- `assets/` → icon notes, visuals  
- `CHANGELOG.md` → version history  

---

## 🚀 Usage

1. Navigate into the GPT’s directory.  
2. Review/edit `prompt/system.md` and `config/metadata.yaml`.  
3. Copy content into the GPT Builder in the ChatGPT UI.  
4. Upload any referenced knowledge files.  
5. Run the tests in `tests/conversations/` manually in the builder to validate.  

---

## 📝 License

Each GPT defaults to the MIT license unless otherwise specified.  
