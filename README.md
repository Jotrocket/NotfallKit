# NotfallKit – A Digital Emergency Plan for Freelancers

**NotfallKit** is an open-source, local-first application that helps freelancers and solo-entrepreneurs document critical digital information in case of illness, incapacity, or death.

**Status:** Under development – not yet usable. First release expected Q4 2025.

## Purpose

Freelancers and solo-entrepreneurs often manage all their digital infrastructure alone. In the event of illness, incapacity, or death, critical logins, instructions, and digital assets may become inaccessible — causing legal, financial, or operational issues.

**NotfallKit** aims to close this gap with a simple, local-first tool that helps users prepare a digital emergency plan. It allows trusted individuals to take over if needed — securely, transparently, and without relying on third-party platforms or cloud services.

## Key Features

- 100% local storage – no cloud or external APIs
- Strong encryption using AES-256 or GPG
- Step-by-step onboarding wizard for non-technical users
- Emergency contact configuration and fallback logic
- Export to encrypted PDF or printable QR-code archive
- Periodic reminder system (fully local, no internet)
- Support for German and English
- Open-source and extensible

## Planned Stack

- **Frontend:** Vue.js or Svelte (to be decided based on performance)
- **Encryption:** Native Web Crypto API / OpenPGP.js
- **Local Storage:** IndexedDB (PWA) or SQLite (Electron)
- **Export:** pdf-lib or HTML-to-PDF for printable output
- **Container:** Electron for desktop / PWA for browser

## Milestones (Provisional)

1. **Month 1–2**  
   - Project setup  
   - Core architecture  
   - Basic encryption logic

2. **Month 2–3**  
   - UI design  
   - Onboarding wizard  
   - Emergency contact setup

3. **Month 4**  
   - Export features  
   - PDF/QR logic  
   - Reminder system

4. **Month 5–6**  
   - Testing (Win/macOS/Linux)  
   - Documentation (EN/DE)  
   - Public release via GitHub

## Contact

- Author: Andreas Weiss  
- Email: NotfallKit@jotrocket.com  
- NLnet Submission Code: 2025-08-147

## License

This project is licensed under the [MIT License](LICENSE).
