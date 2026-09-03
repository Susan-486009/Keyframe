# KeyFrame — Nigeria National Routine Immunisation Milestone Tracker
> Webbo3 Academy Frontend Development Track · Pod Build Project · KeyFrame Pod

A child health card is a piece of paper that gets wet, lost, and left behind. KeyFrame is a lightweight, mobile-first static web platform designed for Nigerian parents and healthcare professionals. It lays out the national routine immunisation schedule with clarity, translating clinical jargon into plain language so a missed date is an informed decision rather than an accident.

---

## 1. Problem Understanding & Grounded Research
Nigeria carries approximately **2.1 million zero-dose children** (UNICEF 2024 Situation Analysis) — the largest number globally. While routine vaccines supplied by the National Primary Health Care Development Agency (NPHCDA) are 100% free by law, systemic drop-off occurs due to:
1. **Paper Fragility:** The physical Yellow Card is easily soaked, torn, or misplaced during moves, leaving caregivers blind to which doses remain.
2. **The 5-Month Silence Gap:** After the 14-week visit, there is a 5-month hiatus before the 9-month Measles and Yellow Fever visit. Over 30% of children drop out during this silence.
3. **The Restart Myth & Fear of Scolding:** Caregivers falsely believe that if an appointment is delayed, they must restart the entire cycle from birth, or they stay away due to fear of nurse reprimands.

KeyFrame eliminates this cognitive load with a clean 10-second date finder, clear what-to-bring checklists, and an honest catch-up protocol.

---

## 2. Brand Thinking & Identity
* **Identity Mark:** A sleek, monoline silhouette combining a mother embracing her child with an ascending arc of progressive milestone nodes (keyframes). The active milestone is highlighted in terracotta.
* **Palette (Strictly Flat, No Gradients):**
  - `--brand: #1B4D3E` (Forest Green — National vitality, authority, and public healthcare trust)
  - `--brand-dark: #102E25` (Deep Spruce — High-contrast typography and footer)
  - `--accent: #C85A17` (Burnt Terracotta/Ochre — Active milestone nodes and alerts)
  - `--brand-surface: #EAF2ED` (Pale Sage — Status badges and gentle highlights)
  - `--paper: #FBF9F5` (Warm Linen — Sunlight-legible background)
* **Typography:**
  - Display: `Space Grotesk` (Google Fonts) — Structural clarity, modern public utility.
  - Body: `Plus Jakarta Sans` (Google Fonts) — Friendly, highly legible on small Android screens.
* **Tone of Voice:** Reassuring, Pragmatic, Grounded.

---
## 3. Ten Roles & Team Contributions

Every page was built with pure semantic HTML5 and CSS3, adhering strictly to `css/brand.css`.

| Seat | Member | Role | Page Built | Duty |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **Chukwuemelieogu Emmanuel Edokobi** | Brand Keeper | `index.html` + `landing.css` | Passed the 10-second milestone test; established the hero and visual rhythm. |
| **02** | **Peter Olajide** | Research Keeper | `problem.html` + `problem.css` | Documented the 2.1M zero-dose crisis and the 5-month drop-off diagram. |
| **03** | **Sulaiman Abdulhameed Adekunle** | Brand Sheet Owner | `how-it-works.html` + `how-it-works.css` | Created `css/brand.css`, maintaining the 6-step spacing tokens and palette. |
| **04** | **Adebayo Susan** | Content Realism | `schedule.html` + `schedule.css` | The Main Working Page. Full NPHCDA schedule with zero placeholder text. |
| **05** | **Adeoye Joshua Adebayo** | Consistency Check | `detail.html` + `detail.css` | Deep-dive into the 6-Week visit: reactions, administration, and home care. |
| **06** | **Winner Kubeyinje** | Accessibility Check | `trust.html` + `trust.css` | Honest catch-up guidelines, nurse scripts, and accessible table markup. |
| **07** | **Afolabi Olawale** | Forms and Flows | `request.html` + `request.css` | Clinic packing checklist, cash estimates, and accessible form controls. |
| **08** | **Unassigned** | Copy and Tone | `guide.html` + `guide.css` | Seat included in the pod structure as required by the assignment. |
| **09** | **ABIDEMI DAMILOLA ISAIAH** | README Owner | `pod.html` + `pod.css` | Repository documentation, team roster, and Webbo3 compliance checks. |
| **10** | **Olaleye Micheal** | Navigation & Deploy | `contact.html` + `contact.css` | Universal header/footer shell, PHC directory, and Vercel deployment. |
---

## 4. Technical Constraints
- Built entirely in **HTML5 & CSS3** (No React, Vue, Tailwind, or JavaScript).
- Lightweight and bandwidth-optimized for mobile 2G/3G connections across Nigeria.
- Strict token-driven design via CSS Custom Properties.
