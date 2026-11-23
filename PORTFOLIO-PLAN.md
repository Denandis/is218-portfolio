# Portfolio Plan — "Where do I fit in AI?" (a career field guide + portfolio)

**Author:** Nandish Desai — IS218, Building Web Applications (Fall 2026)
**Stage:** Plan review (research + decisions). No finished website is due at this stage.
**Career research site:** _add your published Pages URL here_
**Repository:** _add this repo's URL here_
**Creative-project research site (cross-link):** https://denandis.github.io/is218-creative-project/

---

## 1. Question, goal, and reader

**Question.** Which AI career direction fits me best right now — building AI solutions in the field (Forward-Deployed / Applied AI Engineering), or building AI inside healthcare — and what do real employers actually ask for?

**Goal.** Use real job postings to (a) decide a direction to aim my portfolio and learning at, and (b) sharpen my GitHub and LinkedIn with the skills employers repeat.

**Reader (audience).** An early-career candidate like me — an NJIT student deciding between AI directions in the NY/NJ area. The portfolio also has to work for a second reader: a recruiter who skims it in under a minute.

---

## 2. Three real job postings I researched (evidence)

All three opened and checked **Nov 23, 2026**. Postings expire — these are snapshots.

| Role (type) | Employer | Level / Pay | What they ask for | Source |
|---|---|---|---|---|
| **Forward Deployed Software Engineer** (FDE) | Palantir | ~1+ yr · $135K–$200K | Work directly with customers to understand problems and build data-driven solutions; Python, Java, TypeScript/JavaScript; architecture + executive communication | jointaro.com listing / illinoisjoblink.illinois.gov |
| **Senior Machine Learning Research Engineer, AIML** (AI tech role) | Apple | Senior · $184,700–$324,800 + equity | Polished coding; passion for ML & computational science; (research variant values publications at ML conferences) | jobs.anitab.org/companies/apple |
| **AI/ML Engineer** (AI in another industry: healthcare) | Optum (UnitedHealth Group) | 3+ yr · $99K–$176K | Design/deploy Generative AI & ML (LLMs, RAG, agentic frameworks) for healthcare claims; Python, Databricks, PySpark; Git/GitHub; healthcare-data compliance | builtin.com / careers.unitedhealthgroup.com |

**A second FDE data point (for context):** Anthropic's "Forward Deployed Engineer, Applied AI" embeds with customers to ship AI apps; $200K–$300K; Python/Java/TypeScript/Go/Rust/AWS; bachelor's or equivalent; ~25% travel.

**Skills that repeat across postings (what to learn):** Python (nearly universal), a cloud platform (AWS/Azure/GCP), an ML framework (PyTorch/TensorFlow), MLOps / model deployment, and Git/GitHub. Customer-facing communication shows up heavily in the FDE path; healthcare data + compliance shows up in the Optum path.

### Eligibility & my gaps (honest)

| Role | What makes you eligible | My current gaps (what to build) |
|---|---|---|
| Palantir FDE | Degree + ~1+ yr post-college experience; Python/Java/TypeScript; customer-facing communication. Some FDE roles also require U.S.-person status or a security clearance. | I'm still a student with limited post-college experience; need more production/customer-facing work. (Clearance/eligibility specifics stay in my private Canvas reflection.) |
| Apple Sr ML (Research) Engineer | Senior-level; strong ML depth + polished coding; research variant expects ML-conference publications and often an advanced degree. | This is senior/research — above entry level. I'd target a junior ML role first; need real ML/deep-learning depth and a portfolio project. |
| Optum AI/ML Engineer | ~3+ yrs; Master's often preferred; Python, Databricks/PySpark, LLMs/RAG; healthcare-data experience. | Need the degree + a couple years, plus cloud/Databricks and LLM practice. **Advantage:** I already work in healthcare (Optum), which is real domain context. |

*Only professional, public-appropriate info goes here. Personal eligibility circumstances (status, etc.) stay in the private Canvas reflection, as the assignment requires.*

---

## 3. Two career directions compared, and my lean

| | **A — Applied / Forward-Deployed AI Engineering** | **B — AI in Healthcare** |
|---|---|---|
| The work | Embed with customers; build and deploy AI solutions in the field | Build AI/ML for health systems (claims, patient data) |
| Core skills | Python + full-stack + strong communication; deploy fast | Python + ML/LLMs + healthcare data & compliance |
| Pay signal | High ($135K–$300K at Palantir/Anthropic) | Solid ($99K–$176K at Optum), huge employer |
| Fits me because | I like building end-to-end and explaining it | I already work at a pharmacy (Optum) — real domain context |
| Risk for me | True entry-level FDE roles are rare; very competitive | Needs more ML depth than I have yet |

**My lean:** Direction **B (AI in Healthcare)** as the near-term target, because my pharmacy/Optum experience is a real, rare advantage and the employer is in my backyard — while deliberately building the **Python + communication** strengths that also keep Direction A open. The portfolio will show both but aim its projects at healthcare-flavored AI.

*(This is a lean, not a final life decision — the private reflection stays in Canvas as instructed.)*

---

## 4. Two brand / layout directions for the site

- **Direction 1 — "Field Guide."** Clean, editorial, numbered sections, calm neutral + one accent color, scannable cards. Reads like a printed reference (matches the instructor examples). Best for the "help a reader choose" goal.
- **Direction 2 — "Builder / Terminal."** Dark theme, monospace accents, project-forward, GitHub-style. Puts my repos and code front and center. Best for the "impress a recruiter fast" goal.

**Plan:** prototype both headers/hero sections, get peer feedback, then pick one. Current lean: Field Guide for the research site, Builder vibe for the personal portfolio home.

---

## 5. User stories (3–5)

1. *As a recruiter, I want to see Nandish's top skills and projects within a minute so I can judge fit quickly.*
2. *As a fellow student, I want to compare two AI directions backed by real postings so I can choose one to aim at.*
3. *As a skeptical reader, I want to open the actual job postings he cites so I can trust the claims.*
4. *As a learner, I want to see which skills repeat across postings so I know exactly what to study next.*
5. *As Nandish, I want the site to link my GitHub and LinkedIn so readers can verify my real work.*

---

## 6. How this improves my LinkedIn & GitHub (real evidence → real changes)

- **LinkedIn headline/About:** lead with "IT @ NJIT · building AI projects, healthcare-curious (Optum)" and list the repeating skills (Python, Git, a cloud, an ML framework).
- **GitHub:** pin my IS218 projects (the RPS → "Streak" app), write clear READMEs, and keep green CI — exactly the "real work" the postings reward.
- **Skills to add/learn next (from the evidence):** one cloud platform basics, PyTorch or TensorFlow intro, and an MLOps/deployment demo.

---

## 7. Site plan (it's a static site — scaled to match)

This is a small static website, so the plan stays light on purpose.

- **Information architecture (pages/sections):** Home/hero → The 3 roles (evidence) → Compare directions → Eligibility & gaps → Two layouts → User stories → Sources. A separate portfolio home will add: About me, Projects (links to my GitHub repos, including the "Streak" app), and Contact (GitHub + LinkedIn).
- **Reusable components:** top nav, a repeatable "role card," a "source citation" block, and a footer that cross-links my two research sites. Build once, reuse on every page.
- **Accessibility:** semantic headings (one H1, ordered H2s), high-contrast text, descriptive link text, alt text on any images, and keyboard-reachable links.
- **Mobile layout:** single-column stacking; the grids collapse to one column and the nav wraps on small screens (already handled with CSS media queries).
- **Checks:** links resolve (**planned** — run a link check), site deploys on GitHub Pages (**observed** once live), renders on a phone (**planned** — test on my phone), HTML is valid (**planned**).
- **What I deliberately do NOT need (and why):** no database (content is static text), no backend server (GitHub Pages serves static files), no user accounts (nobody logs in), and no design patterns (a few HTML pages don't need them). Adding any of these would be complexity for show, not for the reader.

---

## Project record — Changed / Checked / Next

- **Changed:** Picked my question and reader; researched 3 real job postings (Palantir FDE, Apple MLE, Optum healthcare AI) with sources, dates, responsibilities, and eligibility/gaps; compared two career directions and stated a lean; defined two brand/layout directions and a static-site plan; wrote 5 user stories; published a career research site; identified concrete LinkedIn/GitHub improvements.
- **Checked:** All three postings opened and dated **Nov 23, 2026** — **observed**. Skill-overlap read across postings — **observed** (informal, not a formal count). Peer review of the site — **planned**.
- **Next:** Get a classmate to open a source and flag a confusing part; log feedback as GitHub issues; build the chosen layout; apply the LinkedIn/GitHub edits.
