**KCAPP FRAMEWORK**

*Knowledge-Centered Adaptive Publishing Protocol*

**VERSION 3.2**

**COMPLETE IMPLEMENTATION GUIDE**

*Professional Study Guide & Textbook Creation System*

Multilingual Output  |  AI Prompt Integration  |  Buildable Online Exam Simulation  |  Amazon Competitive Research

*Document 1 of 3 — see also: KCAPP v3.2 Instruction Prompt, KCAPP v3.2 Exam Online Simulation Framework*

Bookkify Publishing System  |  Confidential Internal Use

# **UPGRADE NOTES**

## **What's New in KCAPP v3.2**

KCAPP v3.1 introduced a Digital Companion concept but only produced a specification handoff — a document describing a website, not a working one. User testing confirmed this did not work: nothing was actually built, and no real Netlify site was ever produced. KCAPP v3.2 fixes this by adopting a proven, fully buildable Online Exam Simulation Framework and splitting KCAPP into three synced documents so the manuscript, the operating instructions, and the simulator build spec never drift out of alignment.

| THE THREE-DOCUMENT SYSTEM (NEW IN v3.2) 1\. KCAPP v3.2 Framework (this document) — defines the manuscript standard: content, chapters, front/back matter, image prompts, and how the book hands off to the simulator. 2\. KCAPP v3.2 Instruction Prompt — the exact prompts and session workflow to run both the manuscript build and the simulator build in one connected session. 3\. KCAPP v3.2 Exam Online Simulation Framework — a self-contained, buildable specification for the actual HTML/CSS/JavaScript static exam simulator, packaged Netlify Drop-ready. This is the document that fixes the 'the Netlify site doesn't work' problem: it produces real files, not a brief. All three share the same title, subtitle, chapter count, target market, and language settings from Phase 0–1 of this Framework. Nothing in the simulator should be invented independently of what the book actually promises. |
| :---- |

| UPGRADE 1 | Buildable Simulator, Not a Spec — the companion is no longer a written brief handed to a future developer. It is an actual static website (index.html, style.css, script.js, questions.js) packaged as a Netlify Drop-ready zip, per the new sibling Exam Simulation Framework. |
| :---- | :---- |
| **UPGRADE 2** | Dynamic Full-Length Test Count — the number of full-length practice tests in the simulator is extracted directly from the confirmed book title/subtitle (e.g., '5 Full-Length Practice Tests'), not assumed or defaulted to 3\. |
| **UPGRADE 3** | Setting 5 Rebuilt — Digital Companion Configuration now collects the exact inputs the simulator build needs: number of full-length tests, questions per test, time limit, and readiness/passing score, alongside the retained in-book Knowledge Check depth. |
| **UPGRADE 4** | Simulator Callouts Point to One Practice Centre — because tests are full-length (not chapter-scoped), every in-book Companion Callout and the Companion Access Card link to the same practice-centre dashboard rather than separate per-chapter deep links. |
| **UPGRADE 5** | Simplified Access Code — a single, light-touch access code (no account creation), matching the proven Exam Simulation Framework model, replaces the more complex per-edition/per-unit code architecture explored in v3.1. |
| **UPGRADE 6** | Phase 4B Now a Handoff Phase — this Framework's Phase 4B locks the shared inputs (title/subtitle test count, target market, access code) and then hands off in full to the KCAPP v3.2 Exam Online Simulation Framework, which owns all simulator build detail going forward. |
| **UPGRADE 7** | Answer Randomization Protocol (Retained) — still governs the in-book Knowledge Check pool; the simulator's own no-repetition and difficulty-balance rules are owned by the Exam Simulation Framework. |
| **UPGRADE 8** | Image Prompt Integration (Retained) — unchanged from v2.3.2/v3.1. |
| **UPGRADE 9** | Mandatory Final Formatting Sample Input (Retained) — user must upload a PDF or DOCX sample (maximum 5 MB) before Phase 1\. |

| WHY v3.1's COMPANION SYSTEM DIDN'T WORK v3.1 asked the AI to describe a companion website and hand off a 'Companion Content Package' as a build brief for someone else to implement later. In practice this meant no working site was ever produced in-session, and 'create the Netlify site' had no concrete deliverable behind it. v3.2 corrects this: the sibling Exam Simulation Framework is written as a direct build specification producing actual HTML/CSS/JS files, ready to drag into Netlify Drop in the same session. |
| :---- |

# **PHASE 0**

## **Session Initialization Screen — 8 Settings**

Present this screen at every new KCAPP session. All 8 settings must be confirmed before Phase 1 begins. Type GO or press Enter after confirming all settings.

### **SETTING 1 OF 8 — Output Language**

☐  ENGLISH (Default) — Standard US English, APA academic register

☐  GERMAN — Formal Hochdeutsch, DIN academic register, Sie-form throughout

☐  SPANISH — Neutral Spanish (Latin American standard), academic register

☐  FRENCH — Standard French (international), academic register

| LANGUAGE NOTE System prompts stay in English. All manuscript content, headings, TOC, image captions, front/back matter, and the Digital Companion interface copy generate in the selected language. Amazon subtitles generate in both English AND the target language. |
| :---- |

### **SETTING 2 OF 8 — Primary Target Market**

☐  US / North American — USMLE, NCLEX, PE, LSAT, SAT/ACT, federal regulatory context

☐  UK / European — GMC, NMC, CEng, SQE, EU regulatory frameworks, metric-first

☐  Nigeria / West Africa — MDCN, NUC, ICAN, NHIA context, Nigerian names

☐  Middle East / Gulf — DHA, HAAD, MOH Saudi, SCFHS, Gulf protocols

☐  Spanish-Speaking Latin America — CONAEM, MINSA, regional licensing per country

☐  Germany / DACH Region — Approbationsordnung, DGUV, DIN norms, GKV

☐  Global / Exam-Neutral — No regional personalization

☐  CUSTOM — I will specify my market in detail

### **SETTING 3 OF 8 — Book Sizing Mode (Revised in v3.1, retained in v3.2)**

Select how the book size and chapter count will be calculated. Because full-length practice tests now live on the Digital Companion site, sizing is driven by learning content only.

☐  AUTO-SIZE FROM CHAPTER TARGET (Recommended) — Specify a target chapter count or subject scope; page count auto-calculated from learning-content averages

☐  MANUAL PAGE COUNT — Specify total target pages directly (as in prior versions)

| BOOK CONCISENESS FORMULA Total Pages \= Learning Content Pages ONLY (no assessment-page allowance) Learning Content Pages \= Chapter Count × Average Pages per Chapter In-book Knowledge Checks add negligible length: 3–5 short items per chapter, counted inside the chapter's own page estimate, not as a separate assessment block. Example: 24 chapters × 7 average pages \= 168 learning pages ≈ 175–185 total pages once front/back matter and Companion Access pages are added. |
| :---- |

### **SETTING 4 OF 8 — Image Strategy**

☐  NONE — No image prompts generated

☐  MINIMAL (8–15) — Key image prompts only; chapter anchors

☐  STANDARD (20–35) — One prompt per major section; process flows, comparison charts

☐  RICH (40–60) — One prompt per subsection; step-by-step visuals, infographics

| IMAGE SYSTEM — EMBEDDED IMAGE PROMPTS (Unchanged since v2.3.2) KCAPP v3.2 embeds production-ready image prompts directly in the manuscript instead of inserting AI-generated or stock image files. This system is independent of the Digital Companion system in Setting 5 below — image prompts describe static print visuals; the companion delivers interactive, online experiences. |
| :---- |

### **SETTING 5 OF 8 — Digital Companion Configuration (REVISED in v3.2)**

Configures the buildable online exam simulation that replaces in-manuscript bonus material. These inputs are handed directly to the KCAPP v3.2 Exam Online Simulation Framework, which owns the actual build — this setting only locks the shared facts the simulator needs.

**5a. Number of Full-Length Practice Tests:**

☐  AUTO-EXTRACT FROM TITLE/SUBTITLE (Recommended) — e.g., a confirmed subtitle reading '5 Full-Length Practice Tests' locks this to 5; never defaults to 3

☐  MANUAL ENTRY — user states the exact number directly

**5b. Questions Per Full-Length Test:**

☐  STANDARD — 60–100 questions per test

☐  EXTENDED — 100–150 questions per test

☐  CUSTOM — user specifies exact count

**5c. Time Limit Per Test:**

☐  Matches official exam time limit, if known

☐  CUSTOM — user specifies minutes per test

**5d. Passing / Readiness Score:**

☐  Matches official passing score, if publicly known

☐  READINESS SCORE (Recommended when no official score is public) — uses the four-tier readiness scale from the Exam Simulation Framework

**5e. In-Book Knowledge Check Depth:**

☐  MINIMAL — 3 short knowledge-check questions per chapter, printed in the book

☐  STANDARD — 5 short knowledge-check questions per chapter, printed in the book

| v3.2 DIGITAL COMPANION SYSTEM — WHY IT EXISTS Full-length timed practice tests, detailed scoring, and large answer banks add page count without adding to the book's core teaching value, and they date quickly. KCAPP v3.2 keeps that content current and interactive by building it as a real, working online exam simulation instead of printing it. The manuscript stays lean and readable; the simulator is built and packaged in the same session per the Exam Online Simulation Framework. |
| :---- |

### **SETTING 6 OF 8 — Manuscript Generation Mode**

☐  COMPLETE — Generate entire manuscript in one output (best for books under 200 pages)

☐  CHAPTER-BY-CHAPTER — One chapter at a time; user triggers with 'Next chapter'

☐  PART-BY-PART — Generate by book parts/sections

☐  BATCH CUSTOM — User-defined: 'Generate chapters 3–5', 'Generate Part II'

### **SETTING 7 OF 8 — Competitive TOC Research**

☐  FULL RESEARCH MODE — Deep Amazon competitor analysis before generating TOC (recommended)

☐  QUICK TOC — Use subject classification templates (Phase 4D)

☐  USER-PROVIDED TOC — I will supply my own chapter structure

### **SETTING 8 OF 8 — Final Formatting Sample Document (MANDATORY)**

The user must upload one final formatting sample document before Phase 1 begins. Accepted formats: PDF or DOCX only. Maximum file size: 5 MB. This sample is not source content; it is the visual formatting authority for the final manuscript.

☐  SAMPLE UPLOADED — PDF or DOCX, 5 MB maximum, readable and suitable as a formatting reference

☐  SAMPLE ANALYZED — capture page size, margins, cover/title-page styling, typography hierarchy, heading spacing, chapter opener design, TOC style, headers, footers, page numbering, table/callout styling, image prompt block treatment, and Companion Callout box treatment

☐  SAMPLE COMPLIANCE CONFIRMED — if the sample is missing, too large, unreadable, or not PDF/DOCX, pause the workflow and request a corrected file before continuing

**Type GO after all 8 settings confirmed to begin Phase 1\.**

### **MANDATORY FORMATTING SAMPLE ANALYSIS OUTPUT**

Before Phase 1, display a concise analysis of the uploaded formatting sample: file type, file size, page dimensions, margins, body font, heading hierarchy, title-page design, header/footer behavior, TOC format, table style, callout style, image prompt block style, and how the Companion Callout box (Step 5I) will be styled to match. If any item cannot be determined, state the uncertainty and use the closest safe DOCX equivalent.

# **PHASE 1**

## **Title Reception, Analysis & Subtitle Generation**

*(Unchanged core mechanics from v2.3.2; subtitle formats and compliance filter updated for the online exam simulation in v3.2)*

### **STEP 1A — Title Analysis and Subject Classification**

| Core Subject | Identify exact domain: Academic / Standardized Test / Professional Cert / Skills-Based |
| :---- | :---- |
| **Subject Category** | STEM / Liberal Arts / Social Sciences / Languages / Business / Health / Law / Arts / Test Prep |
| **Complexity Level** | Beginner / Intermediate / Advanced / Expert |
| **Target Audience** | Professional / Academic / Technical / Support Role / Educational |
| **Exam Body** | Adapted to Setting 2 Target Market |
| **Language** | Apply Setting 1 to all generated titles, subtitles, and headers |
| **Market** | Apply Setting 2 to all exam references, scenarios, regulatory bodies |
| **Book Sizing** | If Setting 3 \= AUTO-SIZE FROM CHAPTER TARGET: confirm target chapter count now |
| **Companion Scope** | Confirm Setting 5 practice bank size and simulation package before Phase 2 sizing |
| **Formatting Sample** | Mandatory Setting 8 upload must be validated and analyzed before Phase 1 proceeds |

### **STEP 1B — Amazon-Optimized Subtitle Generation**

Generate exactly 6–8 subtitle options. If language is non-English, generate each in BOTH English AND the target language.

| Format 1 | "Complete Study Guide with \[N\] Full-Length Practice Tests — Free Online Exam Simulation Access" |
| :---- | :---- |
| **Format 2** | "Complete Review Guide — High-Yield Concepts and \[N\] Full-Length Practice Tests Online" |
| **Format 3** | "Study Guide with \[N\] Timed Practice Tests and Instant Scoring Online" |
| **Format 4** | "\[Content Type\] to \[Outcome\] — \[Method\] with \[N\] Full-Length Practice Tests" |
| **Format 5** | "Study Guide and Online Exam Simulation — \[N\] Practice Tests for \[User Type\]" |
| **Format 6** | "Master \[Subject\] with \[Method\] and \[N\] Full-Length Practice Tests" |
| **Format 7** | "Pass the \[Exam Name\] with \[Method\] and \[N\] Free Online Practice Tests" |
| **Format 8** | "Learn \[Skills\] from \[Starting Point\] to \[End Goal\] with \[N\] Full-Length Practice Tests" |

| v3.2 REQUIREMENT — STATE THE EXACT TEST COUNT Every recommended subtitle must state the exact number of full-length practice tests (N) that the Exam Online Simulation Framework will actually build. Do not use vague phrasing like 'practice tests included' without a number, and never default to a placeholder of 3 — confirm the real number with the user in Phase 4B before finalizing the subtitle. |
| :---- |

### **STEP 1C — Amazon Subtitle Compliance Filter**

Run every generated subtitle through this filter BEFORE presenting to user. Reject and regenerate any subtitle that fails.

| RULE 1 — Character Count | Total title \+ subtitle must be under 200 characters. Subtitle alone: 50–150 chars for optimal display. |
| :---- | :---- |
| **RULE 2 — Mobile Display** | Key information must be visible in truncated Amazon search results (approx. 80 chars shown on mobile). |
| **RULE 3 — Banned Terms** | REJECT any subtitle containing: Ultimate, Secret, Guaranteed, \#1, Best Ever, Proven, Foolproof, Instant. Amazon flags these as exaggerated claims. |
| **RULE 4 — No Trademark Violations** | Do not use trademarked exam body names as sales claims (e.g., 'Official NCLEX Guide' is a violation). |
| **RULE 5 — Accurate Representation** | Subtitle must truthfully represent actual book content. No overpromising outcomes. |
| **RULE 6 — Professional Tone** | Tone appropriate for the subject's professional audience. No hype language. |
| **RULE 7 — Digital Companion Disclosure** | Any subtitle or back-cover copy referencing the online exam simulation must not overstate permanence ('lifetime access' is not permitted unless contractually true), must not imply the simulator is an official certification-body product, and must not claim offline functionality it does not have. |
| **RULE 8 — Accurate Test Count (NEW in v3.2)** | The number of full-length practice tests stated in the subtitle must exactly match the number the Exam Online Simulation Framework will build. Never advertise a test count that has not been locked in Phase 4B. |

### **STEP 1D — Compliance Verification Output Block**

After presenting subtitle options, always display this verification block:

| SUBTITLE COMPLIANCE VERIFICATION For each recommended subtitle, display: Character count: \[X\] / 200 maximum Mobile preview (80 chars): "\[First 80 characters shown here...\]" Banned terms check: PASS / FAIL   |   Trademark check: PASS / FAIL Content accuracy check: PASS / FAIL   |   Companion disclosure check: PASS / FAIL Test count accuracy check: PASS / FAIL — stated \[N\] matches locked simulator test count Primary keywords included: \[List\]   |   Target market alignment: \[Market name\] OVERALL: COMPLIANT / NON-COMPLIANT |
| :---- |

**AWAITING SUBTITLE SELECTION before proceeding to Phase 2\.**

# **PHASE 2**

## **Guide Specifications & Content Distribution**

*(Revised in v3.1, retained in v3.2 — page count derives from learning-content pages only; assessment content is not a book-sizing input)*

### **STEP 2A — Content Sizing**

**IF Setting 3 \= AUTO-SIZE FROM CHAPTER TARGET:**

| AUTO-SIZE CALCULATION DISPLAY Show this output after the user confirms a target chapter count or subject scope: Target chapter count: \[N\] Average pages per chapter (complexity-adjusted): \[6/7/8\] Learning content pages: \[N chapters × avg pages\] Front matter \+ back matter \+ Companion Access pages: approx. \[8–14 pages\] GUIDE SPECIFICATIONS CONFIRMED: Total pages: \[N\]  |  Learning content: \[N pages\]  |  Chapters: \[N\] In-book knowledge checks: \[3 or 5 per chapter, per Setting 5c\]  |  Companion practice bank: \[X questions, hosted online per Setting 5a\] |
| :---- |

**IF Setting 3 \= MANUAL PAGE COUNT:**

☐  Standard Study Guide — 100–150 pages

☐  Comprehensive Exam Prep — 150–220 pages

☐  Complete Reference Manual — 220–300+ pages

☐  Custom: \_\_\_\_\_ pages

| WHY THE RANGE SHRANK FROM v2.3.2 v2.3.2 sized the book around a target practice-question count, which could inflate page count well past 350–500 pages once large test banks were printed in full. In v3.2 those full-length tests live in the online exam simulation instead, so manual page targets reflect a learning-content-only book and run shorter by design. |
| :---- |

### **STEP 2B — Dynamic Introduction Sizing**

Introduction length scales to total book length (unchanged from v2.3.2):

| Short guides (under 150 pages) | Introduction: 1.5–2 pages (500–700 words, no subheadings) |
| :---- | :---- |
| **Mid-length guides (150–220 pages)** | Introduction: 4–6 pages (1,500–2,200 words, 2–3 subheadings) |
| **Comprehensive guides (220+ pages)** | Introduction: 8–12 pages (3,000–4,500 words, full subject overview with 4–6 subheadings) |

### **STEP 2C — Content Standards (Mandatory)**

**•**  Educational Authority Language — professional academic/instructional tone throughout

**•**  Zero AI-Generated Vocabulary — no robotic phrasing; natural human instructor voice

**•**  NO BULLET POINTS IN LEARNING CHAPTERS — prose paragraphs only

**•**  No Full-Length Practice Tests in the Manuscript — full-length tests, answer banks, and simulations belong in the Exam Online Simulation Framework build, not the printed chapter

**•**  Exact Q\&A Template for In-Book Knowledge Checks — same format standard as full tests, scaled down to 3–5 items

**•**  Student-Centered Terminology — 'You will learn' not 'This guide covers'

**•**  Competency-Based Progression — prerequisites defined, knowledge checks embedded

# **PHASE 3**

## **Reference Material & Research Methodology**

*(Unchanged from prior versions — three options below)*

| OPTION 1: EXAM-SPECIFIC REFERENCE MATERIALS User uploads exam blueprints, official guides, syllabi, practice exams. Content aligned precisely to official exam specifications and domain weightings. Practice questions tailored to specific exam format and style, whether printed as a knowledge check or built into the online exam simulation. Materials accepted: PDF, Word, TXT, image files. Multiple files welcome. |
| :---- |

| OPTION 2: COMPREHENSIVE EDUCATIONAL RESEARCH Professional research using authoritative educational/certification sources. Minimum 5–7 authoritative sources per major exam domain. Original practice questions created from publicly available exam specs. No direct copying of copyrighted materials — strict academic integrity. Evidence-based study strategies from educational psychology research. |
| :---- |

| OPTION 3: HYBRID — EXAM MATERIALS \+ EDUCATIONAL RESEARCH Phase 1: Analyze user's uploaded materials as primary foundation. Phase 2: Identify content gaps and study strategy enhancement opportunities. Phase 3: Targeted educational research to fill identified gaps. Best of both: exam-specific accuracy \+ evidence-based study science. |
| :---- |

# **PHASE 4 — COMPETITIVE RESEARCH**

## **Amazon Competitive TOC Research Engine**

Active when Setting 7 \= FULL RESEARCH MODE. Skip to Phase 4D if Setting 7 \= QUICK TOC.

### **STEP 4-R1 — Competitor Identification**

**1\.**  Search Amazon: \[title/exam keyword\] \+ 'study guide' and 'exam prep'

**2\.**  Identify top 5 best-sellers (BSR \< 50,000 preferred)

**3\.**  For each: Title, Subtitle, Author, BSR, Pages, Stars, Reviews, Publication year

**4\.**  Extract TOC from Look Inside previews where available; note whether competitors print full test banks in-book or offer any digital companion of their own

### **STEP 4-R2 — Gap Analysis**

**•**  COVERAGE GAPS — topics all competitors include vs. topics missing

**•**  DEPTH GAPS — areas where competitors are shallow

**•**  FORMAT GAPS — missing digital practice access, interactive exercises, mnemonics

**•**  AUDIENCE GAPS — underserved niches (bilingual, clinical role, regional)

**•**  RECENCY GAPS — outdated editions; opportunity to be most current, especially in the companion question bank which can be refreshed after publication

**•**  MARKET FIT GAPS — competitors not serving Setting 2 target market

### **STEP 4-R3 — Winning TOC Construction**

**5\.**  MUST-HAVE TOPICS — every topic covered by 3+ competitors

**6\.**  DIFFERENTIATION TOPICS — 2–4 chapters covering identified gaps

**7\.**  MARKET-SPECIFIC CHAPTERS — 1–2 chapters for Setting 2 regional context

**8\.**  DEPTH SEQUENCING — foundational to advanced; match exam blueprint weights

**9\.**  PREMIUM SECTIONS — Clinical Scenarios, Mnemonic Vaults, Quick-Reference Appendix (print); Simulations and Full Practice Bank (companion site)

**10\.**  LANGUAGE ALIGNMENT — Setting 1 non-English: titles in target language (English in parentheses)

### **STEP 4-R4 — TOC Presentation**

| COMPETITIVE TOC OUTPUT FORMAT TITLE: \[Full Title \+ Subtitle\] FRONT MATTER: Preface | About This Guide | How to Use This Guide | How to Access Your Digital Companion | About the Exam INTRODUCTION (\[dynamic length per Setting 2B\]) CHAPTER 1: \[Title\] — \[Why this wins vs. competitors\] CHAPTER 2: \[Title\] — \[Gap this fills\] ... CHAPTER N: \[Title\] — \[Differentiation note\] BACK MATTER: Conclusion | Knowledge Check Answer Key | Glossary | References | Companion Access Card COMPETITIVE ADVANTAGE SUMMARY: Topics competitors miss that we cover: \[List\] Unique chapters: \[List\] Target market personalization: \[List\] Estimated pages: \[Range\]  |  Companion practice questions: \[X\]  |  Simulations: \[Y\] |
| :---- |

**AWAITING TOC APPROVAL before Phase 4B begins.**

### **STEP 4D — Template TOC by Subject (Quick TOC Path)**

| Medical / Healthcare (9 ch) | Ch1: Foundational Concepts | Ch2: Pathophysiology | Ch3: Diagnostics | Ch4: Treatment Protocols | Ch5: Pharmacology | Ch6: Patient Safety | Ch7: Clinical Scenarios | Ch8: High-Yield Review | Ch9: Final Review |
| :---- | :---- |
| **Engineering / STEM (12 ch)** | Ch1: Fundamental Principles | Ch2: Core Concepts | Ch3: Design Standards | Ch4: Calculations | Ch5: Advanced Applications | Ch6: Safety/Compliance | Ch7: Professional Ethics | Ch8: Applied Problem-Solving | Ch9: Exam Strategy | Ch10: Specialized Topics | Ch11: Project Mgmt | Ch12: Continuing Education |
| **Professional Licensing (9 ch)** | Ch1: Regulatory Framework | Ch2: Core Competencies | Ch3: Professional Responsibilities | Ch4: Practical Application | Ch5: Advanced Concepts | Ch6: Compliance/Legal | Ch7: Continuing Education | Ch8: Exam Readiness | Ch9: Exam Techniques |
| **Academic Course (15 ch)** | Ch1–3: Foundations | Ch4–6: Core Applications | Ch7–9: Advanced Analysis | Ch10–12: Synthesis & Research | Ch13–15: Professional Development |

*Note: chapter counts that formerly included a dedicated 'Practice Questions' or 'Practice Exams' chapter (e.g., Ch8 in the v2.3.2 Medical and Licensing templates) are replaced with a high-yield review or exam-readiness chapter; the full practice bank moves to the Digital Companion.*

# **PHASE 4B — DIGITAL COMPANION HANDOFF (REVISED IN v3.2)**

## **Locking Shared Inputs, Then Handing Off to the Exam Simulation Framework**

Runs once, after TOC approval and before manuscript generation. In v3.2 this phase does two things only: (1) lock the handful of facts the simulator build needs, and (2) hand off entirely to the KCAPP v3.2 Exam Online Simulation Framework, which owns every remaining decision about the simulator's design, files, and packaging. This Framework does not duplicate simulator build detail — see the sibling document for that.

### **STEP 4B-1 — Lock the Shared Inputs**

| Number of Full-Length Tests | Extracted from the confirmed title/subtitle per Setting 5a. This is the single most important number — it must never default to 3\. |
| :---- | :---- |
| **Questions Per Test / Time Limit / Readiness Score** | Per Setting 5b–5d. |
| **Exam Name, Year Range, Target Market** | Carried over from Phase 1 title analysis and Setting 2\. |
| **Access Code** | One simple, light-touch code printed in the book (e.g., a short memorable string). No account creation, no per-unit serialization — see the Exam Simulation Framework's Access Code Rule. |
| **Brand / Colour Preference** | Optional — carry over any cover or brand colour preference so the simulator's visual theme can match. |

### **STEP 4B-2 — Handoff Statement**

| HANDOFF TO THE EXAM ONLINE SIMULATION FRAMEWORK At this point, open and follow the KCAPP v3.2 Exam Online Simulation Framework in full, using the locked inputs from Step 4B-1. That document governs: the simulator's landing page, dashboard, test-taking flow, question data structure, scoring, visual design, device responsiveness, file structure, Netlify Drop packaging, README, and QR code book-page copy. It produces real, working files — not a specification for someone else to build later. Do not re-derive simulator design decisions in this Framework. If the two documents ever seem to disagree, the Exam Online Simulation Framework is authoritative for anything about the simulator itself; this Framework is authoritative for anything about the printed manuscript. |
| :---- |

### **STEP 4B-3 — What Comes Back to This Framework**

Once the Exam Online Simulation Framework produces the simulator package, three things return to the manuscript workflow:

**•**  The live Netlify URL (or a placeholder pending upload) for the Companion Callout boxes and Companion Access Card

**•**  The access code confirmed in Step 4B-1, for printing in the front matter and back matter

**•**  The exact number of full-length tests and any headline feature (e.g., flashcards, readiness checklist) to reference in Companion Callout wording

| WHY THIS PHASE GOT SHORTER IN v3.2 v3.1 tried to define the companion website's architecture inside this Framework, which duplicated and sometimes conflicted with the actual build logic. v3.2 keeps this Framework focused on the book and delegates all simulator build decisions to one authoritative sibling document. |
| :---- |

# **PHASE 5 — MANUSCRIPT ENGINE**

## **Full Manuscript Generation with Image Prompt & Companion Integration**

Activated after Phase 4B locks the shared simulator inputs and, ideally, after the Exam Online Simulation Framework has produced a live or placeholder Netlify URL. Generates publishing-house-grade content with embedded image prompt blocks and Companion Callout boxes instead of printed full-length practice tests or generated image files.

### **STEP 5A — Pre-Generation Checklist**

☐  Phase 0: all 8 settings confirmed

☐  Title and subtitle confirmed \+ compliance verified (Phase 1\)

☐  Guide specifications and learning-content sizing confirmed (Phase 2\)

☐  Research approach selected and complete (Phase 3\)

☐  Table of Contents approved (Phase 4\)

☐  Shared simulator inputs locked and handed off to the Exam Online Simulation Framework; live or placeholder Netlify URL and access code returned (Phase 4B)

☐  If AUTO-SIZE: chapter target confirmed and size calculated

| GENERATION TRIGGER GENERATE \[scope\] — scope options: ALL | CHAPTER \[N\] | CHAPTERS \[N-M\] | PART \[N\] | FRONT MATTER | BACK MATTER | COMPANION PACKAGE |
| :---- |

### **STEP 5B — Manuscript Architecture — Dynamic Niche Typography**

### **Final Formatting Sample Override**

The uploaded final formatting sample is the primary visual authority. The niche typography profiles below provide fallback rules only when the sample does not define a specific element, including the Companion Callout box introduced in Step 5I.

Analyze confirmed title and subject category. Apply the matching niche profile:

| MEDICAL / HEALTHCARE / NURSING / PHARMACY Body: Times New Roman 12pt | H1: 16pt bold black | H2: 14pt bold dark gray | H3: 12pt bold gray Spacing: 1.15 body, 1.0 tables | Margins: 1 inch all | Para: 6pt before, 8pt after Rationale: Clinical publishing standard readers already trust. |
| :---- |

| ENGINEERING / TECHNICAL / STEM Body: Arial 11pt | H1: 16pt bold navy | H2: 13pt bold blue | H3: 11pt bold teal Spacing: 1.15 body, 1.0 formulas/tables | Margins: 1 inch | Para: 4pt before, 6pt after Rationale: Tighter sans-serif improves scanability for reference readers. |
| :---- |

| PROFESSIONAL LICENSING / BUSINESS / FINANCE / LAW Body: Garamond 12pt or Calibri 12pt | H1: 18pt bold navy | H2: 14pt bold dark blue | H3: 12pt bold gray Spacing: 1.25 body, 1.0 tables | Margins: 1.25 inch left, 1 inch all others | Para: 8pt before, 10pt after Rationale: Wider left margin and formal spacing signal authority. |
| :---- |

| ACADEMIC / UNIVERSITY COURSE EXAM PREP Body: Times New Roman 12pt | H1: 16pt bold black | H2: 13pt bold black | H3: 12pt bold italic black Spacing: 1.5 body (APA/MLA), 1.0 tables | Margins: 1 inch | Para: 0pt before, 12pt after Rationale: Mirrors APA/MLA coursework students already know. |
| :---- |

| SKILLS-BASED / TRADE / VOCATIONAL Body: Calibri 12pt | H1: 18pt bold navy | H2: 14pt bold blue | H3: 12pt bold teal Spacing: 1.15 body | Margins: 1 inch | Para: 6pt before, 8pt after Rationale: Clarity-first; no strong convention pressure in this niche. |
| :---- |

| LANGUAGE / BILINGUAL / ESL Body: Calibri 11pt | H1: 16pt bold navy | H2: 13pt bold blue | H3: 11pt bold teal Spacing: 1.3 body (looser for non-native readers) | Margins: 1 inch | Para: 6pt before, 10pt after Bilingual: Setting 1 non-English uses italic 10pt gray for English reference text. Rationale: Looser spacing reduces cognitive load. |
| :---- |

| DEFAULT FALLBACK Body: Calibri 12pt | H1: 18pt bold navy | H2: 14pt bold blue | H3: 12pt bold teal | H4: 12pt bold gray Spacing: 1.15 body, 1.0 callouts | Margins: 1 inch | Para: 6pt before, 8pt after |
| :---- |

### **STEP 5C — Front Matter Structure (Revised)**

| Half Title Page | Title only, centered — page i |
| :---- | :---- |
| **Title Page** | Full title, subtitle, author, edition — page iii |
| **Compliance Page** | Compliance, ISBN placeholder, publisher, disclaimer — page iv |
| **Dedication** | Optional, 1–3 lines centered — page v |
| **Table of Contents** | Auto-generated from H1/H2 headings |
| **Preface** | 400–600 words: author purpose, audience, how to use |
| **How to Use This Guide** | 300–400 words: navigation, icons, study schedule |
| **How to Access Your Digital Companion (Revised in v3.2)** | 250–350 words plus the front-matter QR code and printed access code (per Phase 4B-1). Explains in plain language what the online exam simulation offers — the exact number of full-length timed practice tests, instant scoring, answer explanations, flashcards, and readiness checklist — and how to scan or type the URL. States plainly that it is a free practice tool, not the official exam. |
| **About the Exam** | 500–700 words: format, scoring, registration |
| **Introduction** | Dynamic length per Step 2B — prose, no bullet points |

### **STEP 5D — Chapter Structure (Each Chapter, Revised)**

| Chapter Opener | Chapter number badge, title, 2-sentence overview paragraph |
| :---- | :---- |
| **Learning Objectives** | 4–8 Bloom's taxonomy objectives in PROSE paragraph — NOT a bullet list |
| **Key Terms** | Callout box: 6–10 terms with one-line definitions |
| **Body Content** | 2,500–5,000 words — natural paragraph prose, no bullets |
| **Image Prompts** | Embedded per Setting 4 density (see Step 5F) |
| **Applied Examples** | 1–3 scenario boxes; adapted to Setting 2 target market |
| **Mnemonics / Memory Aids** | 1–2 per chapter for high-yield topics |
| **Chapter Summary** | 200–300 word prose paragraph — NOT a bullet list |
| **Knowledge Check (REPLACES Full Practice Questions)** | 3–5 short MCQs per Setting 5c, using the exact Q\&A format from Step 5G — not a full-length test — those are built by the Exam Online Simulation Framework |
| **Knowledge Check Answer Key (chapter)** | Inline below the knowledge check, using the exact answer format from Step 5G |
| **Companion Callout (Revised in v3.2)** | Boxed QR code \+ short prompt text directing readers to the online exam simulation's practice-centre dashboard — not a chapter-specific page, since the simulator is organized around full-length tests rather than per-chapter modules (see Step 5I) |

### **STEP 5E — Back Matter Structure (Revised)**

| Conclusion | 400–600 words prose: synthesis, motivational close, next steps |
| :---- | :---- |
| **Knowledge Check Answer Key, Consolidated** | All in-book knowledge-check answers with full rationale, 50-word cap per answer — this is short by design since it covers only the 3–5 item checks, not a full test bank |
| **Full Glossary** | All key terms alphabetical, 1–3 sentences each |
| **References** | 10–20 entries, APA 7th edition |
| **Companion Access Card (REPLACES Bonus Section)** | One page: master QR code linking to the practice-centre dashboard, printed access code (per Phase 4B-1), and the QR code book-page copy supplied by the Exam Online Simulation Framework, stating the exact number of full-length tests included |
| **About the Author** | 150–250 words, third person, credentials |

| WHAT MOVED OUT OF THE MANUSCRIPT v2.3.2 printed a full 5–10 question test per chapter, a comprehensive answer key covering every question in the book, and a Bonus Section of quick-reference cards or a mnemonic vault. In v3.2, the full-length timed practice tests promised in the title/subtitle are built into the actual online exam simulation by the Exam Online Simulation Framework, and the manuscript carries only the short knowledge check, its brief answer key, and the QR-linked Companion Callout pointing to the simulator. |
| :---- |

### **STEP 5F — Image Prompt Integration Engine (Retained from v2.3.2)**

KCAPP v3.2 embeds detailed image prompt blocks rather than actual images, exactly as in prior versions. This system is unrelated to the Digital Companion — it governs static print visuals only.

### **Image Prompt Construction Protocol**

**1\.**  CONTEXT LOCK — identify the exact paragraph, concept, or process the visual should support.

**2\.**  PROMPT BUILD — write a clear production prompt with subject, setting, composition, lighting, angle, labels, and educational intent.

**3\.**  DIAGRAM MODE — for anatomy, mechanisms, formulas, schematics, or workflows, specify clean labeled educational diagram requirements.

**4\.**  COMPLIANCE LOCK — include caption text and a note to avoid logos, trademarks, watermarks, identifiable private persons, and unsupported claims.

### **Image Prompt Trigger Locations**

**•**  Immediately after chapter opener — establishing context prompt for the chapter subject

**•**  After any 3+ step clinical or technical process — process flow or environment photo

**•**  After any anatomy, mechanism, or system description — labeled educational diagram prompt or clinical-scene prompt

**•**  After any comparison of 2+ treatment approaches or options — side-by-side visual

**•**  After any statistical or data passage — data visualization prompt or professional-setting prompt

**•**  Before each chapter summary — concept-anchoring image prompt

### **Image Prompt Formatting Rules**

| Prompt detail | Minimum 80–120 words for complex visuals; include orientation, subject, style, labels, and caption |
| :---- | :---- |
| **Placement** | Full-width boxed prompt block directly after the relevant paragraph |
| **Caption format** | Figure \[X.Y\]: \[Descriptive caption 10–20 words\] | Image Prompt: \[production-ready prompt text\] |
| **Compliance** | Prompt must avoid protected logos, trademarks, watermarks, identifiable private persons, and copyrighted character styles. |
| **Style direction** | Photorealistic only. Reject: cartoons, clip art, illustrations, watermarked images, low-res thumbnails. |
| **Subject matching** | Prompt must be directly relevant to the paragraph it follows — no generic filler visuals |

### **STEP 5G — Exact Q\&A Formatting Template (Rescoped to Knowledge Checks)**

In v2.3.2 this template governed full chapter tests and the entire back-matter answer bank. In v3.2 it governs the short 3–5 item in-book Knowledge Check; the Exam Online Simulation Framework applies its own equivalent question format. The format itself is unchanged; only where it applies has changed.

### **Question Format — Apply Exactly**

| QUESTION FORMAT TEMPLATE 1\. \[Question stem written as complete sentence with proper punctuation and subject-specific content?\] A. \[First answer option using proper discipline terminology\] B. \[Second answer option with field-appropriate language\] C. \[Third answer option relevant to subject matter\] D. \[Fourth answer option using correct professional terminology\] 2\. \[Next question stem...\] |
| :---- |

### **Answer Format — Apply Exactly**

| ANSWER FORMAT TEMPLATE 1\. B. Brief concept title from the discipline — Concise explanation of why B is correct, using proper terminology. Maximum 50 words. 2\. C. Key identifying phrase — Direct reasoning for correct answer using field-appropriate language. Under 50 words. 3\. A. Core principle name — Why A is the correct answer stated directly. Distractors not discussed unless critical. Maximum 50 words. |
| :---- |

### **STEP 5H — In-Book Knowledge Check Standards & Answer Randomization**

In v3.2 this step covers only the in-book Knowledge Check pool. Question quality, difficulty balance, no-repetition rules, and answer randomization for the full-length practice tests are owned entirely by the KCAPP v3.2 Exam Online Simulation Framework, which applies its own equivalent standards to every test it builds.

### **In-Book Knowledge Check Standards**

**•**  Every question uses the exact Q\&A template from Step 5G

**•**  No in-book Knowledge Check question is duplicated verbatim inside any full-length test built by the Exam Online Simulation Framework — the two pools stay independent

**•**  Explanations stay under the 50-word cap

### **Answer Randomization Protocol (Retained, In-Book Scope Only)**

The in-book Knowledge Check pool must independently pass this check before delivery. This is non-negotiable. (The simulator's own randomization is governed by the sibling document's No Repetition Rule and Difficulty Balance Rule.)

**1\.**  Plan answer distribution BEFORE writing questions: target 25% for each of A, B, C, D across the in-book Knowledge Check pool

**2\.**  NEVER place more than 2 consecutive identical answers

**3\.**  NEVER use predictable patterns (A, B, C, D repeating; A, A, B, B repeating; etc.)

**4\.**  Create an answer distribution chart before writing questions — assign answer letters to question numbers first, then write questions to match

**5\.**  After writing all questions, verify final distribution meets the 25% balance

| DISTRIBUTION CHART METHOD Before writing a 96-question in-book pool (24 chapters × 4 avg), create a plan: Q1=B, Q2=D, Q3=A, Q4=C, Q5=B, Q6=A, Q7=D, Q8=C... Verify: A count=\[24\], B count=\[24\], C count=\[24\], D count=\[24\] Verify: No run of 3+ identical consecutive answers |
| :---- |

### **STEP 5I — QR Code Embedding Protocol (Revised in v3.2)**

Defines how the QR code for the online exam simulation actually gets onto the printed page inside the DOCX manuscript. The QR code image itself and its target URL come from the Exam Online Simulation Framework's completed build (its live Netlify link, or a placeholder pending upload).

| Step 1 — Confirm the target URL | Pull the exact simulator URL from the completed Exam Online Simulation Framework build. If the site has not yet been uploaded to Netlify, use the placeholder format below. |
| :---- | :---- |
| **Step 2 — Generate a real, scannable QR image** | Produce an actual QR code image file for that URL rather than a decorative placeholder graphic. If the live URL is not yet known, insert a clearly labeled placeholder box reading '\[QR CODE PLACEHOLDER — generate once the simulator is uploaded to Netlify; target URL: TBD\]' so the manuscript is never released with a fake or non-functional code. |
| **Step 3 — Embed at print-safe size** | Insert the image at minimum 0.8 in × 0.8 in (20 mm × 20 mm), quiet zone of at least 4 modules, error-correction level M or Q, black modules on a light background only. |
| **Step 4 — Caption immediately below** | Add the plain-language caption, the access code, and the literal URL fallback directly under the image, using the QR code book-page copy supplied by the Exam Online Simulation Framework. |
| **Step 5 — Verify before export** | Before Phase 6 delivery, confirm every embedded QR image actually decodes to the intended URL — do not rely on visual similarity to a correct QR pattern. |

| COMPANION CALLOUT BOX — STANDARD LAYOUT (v3.2) CONTINUE PRACTICING ONLINE \[QR CODE IMAGE — verified to decode to the live simulator URL\] Scan for \[N\] full-length timed practice tests, instant scoring, detailed explanations, flashcards, and a final readiness checklist. Or visit: \[simulator URL\] Access Code: \[code\] |
| :---- |

# **PHASE 6**

## **DOCX Output, Validation & Delivery**

Two deliverables are compiled: the manuscript .docx (this Framework) and the Netlify-ready simulator package (the sibling Exam Online Simulation Framework).

### **STEP 6A — DOCX File Standards**

| Format | .docx (OOXML ISO/IEC 29500\) |
| :---- | :---- |
| **Page Size** | US Letter 8.5 x 11 inch (12,240 x 15,840 DXA) |
| **Body Font** | Per niche profile (Step 5B) |
| **TOC** | Auto-generated from heading styles |
| **Headers** | Title (left) | Chapter name (right) |
| **Footers** | Publisher name (left) | Page number (right) |
| **Image Prompt Placement** | Full-width boxed prompt block with caption below; no image file embedded |
| **QR Code Placement** | Real, scannable embedded image at minimum 0.8 in × 0.8 in with quiet zone, captioned per Step 5I; never a decorative substitute |
| **Chapter Breaks** | New page per chapter with number badge |
| **Answer Randomization** | In-book Knowledge Check pool verified 25/25/25/25 before export |
| **Formatting Sample Match** | Final DOCX must mirror the mandatory uploaded PDF/DOCX sample: page layout, title page, typography, heading hierarchy, spacing, headers/footers, tables, callouts, image prompt block design, and Companion Callout box design |

### **STEP 6B — Pre-Delivery Quality Checklist**

☐  All chapters present in correct order

☐  TOC entries match actual chapter titles

☐  Page numbers sequential

☐  No full-length practice tests, full answer banks, or simulations printed in the manuscript

☐  Every chapter contains a 3–5 item Knowledge Check in exact Q\&A format

☐  Every chapter contains a Companion Callout box with a real, verified-decoding QR image

☐  Access code printed correctly on the Companion Access Card and the front-matter companion page

☐  Subtitle's stated test count matches the number of full-length tests actually built in the simulator

☐  In-book Knowledge Check answer distribution verified: 25% A / 25% B / 25% C / 25% D

☐  No 3+ consecutive identical answers in the in-book pool

☐  All answer explanations under 50 words each

☐  Glossary covers all bolded key terms

☐  References in APA 7th edition

☐  No placeholder text remaining, except an explicitly labeled QR placeholder awaiting Netlify upload

☐  Target market personalization verified

☐  Language consistency verified — no code-switching

☐  Learning chapters contain NO bullet point lists (prose only)

☐  Simulator package independently passed its own Exam Online Simulation Framework checklist (Rules 32–34)

### **STEP 6C — Delivery Confirmation Message**

| DELIVERY MESSAGE TEMPLATE (v3.2 — Three Files) Your \[Title\] manuscript, and your online exam simulation package, are complete. FILE 1 — MANUSCRIPT: Chapters: \[N\] | Total pages: \[N\] | Learning content pages: \[N\] In-book knowledge checks: \[N chapters × 3–5 items\] | Distribution: A=\[N%\] B=\[N%\] C=\[N%\] D=\[N%\] Image prompts embedded: \[N\] | QR codes embedded: \[N\] FILE 2 — EXAM ONLINE SIMULATION PACKAGE (Netlify-ready zip): Full-length tests: \[N, matching subtitle\] | Questions per test: \[N\] | Total questions: \[N\] Access code: \[code\] | Time limit per test: \[N minutes\] | Readiness/passing score reference: \[X%\] FILE 3 — README & QR CODE BOOK-PAGE COPY: upload instructions, suggested QR wording, question audit summary Target market: \[Setting 2\] | Language: \[Setting 1\] Ready for: KDP interior upload | Netlify Drop upload | Author review | ISBN/copyright completion Formatting sample applied: \[filename\] | Type: \[PDF/DOCX\] | Size: \[MB\] | Match status: VERIFIED |
| :---- |

# **PHASE 7**

## **Content Quality Standards & Anti-AI Language Rules**

*(Unchanged from v2.3.2, plus one addition covering Companion Callout phrasing)*

### **BANNED LANGUAGE — Never Use**

| 'In today's rapidly evolving...' | Open with direct patient scenario or bold factual claim |
| :---- | :---- |
| **'It is important to note that...'** | State the important thing directly |
| **'As we have discussed...'** | 'In Chapter 3, you learned...' (specific reference) |
| **'Delve into', 'dive deep'** | 'examine', 'explore', 'analyze', 'review' |
| **'Holistic approach'** | Describe the actual multi-system approach specifically |
| **'Leverage', 'utilize'** | 'use', 'apply', 'employ' |
| **'Embark on a journey'** | 'This chapter walks you through...' |
| **'Robust', 'comprehensive' (overused)** | Describe specifically what makes it robust/comprehensive |
| **Bullet lists in learning chapters** | Prose paragraphs with transitional language instead |
| **Bullet point chapter summaries** | 200–300 word summary paragraph with topic sentences |
| **Bullet learning objectives** | Paragraph starting with 'By the end of this chapter, you will...' |
| **Hype language in Companion Callout boxes ('unlock secret bonuses', 'exclusive vault')** | Plain, accurate description: 'Practice continues online' plus what is actually there |

### **REQUIRED LANGUAGE PATTERNS**

**•**  Second person instructional: 'You will encounter...', 'When you see this on the exam...'

**•**  Direct exam framing: 'The exam tests this concept by asking...', 'A common distractor is...'

**•**  Active clinical scenarios adapted to Setting 2: 'A 45-year-old presents with...'

**•**  Explicit study direction: 'Focus 30% of your study time here', 'High-yield: expect 3–5 questions'

**•**  Honest difficulty: 'This is a challenging calculation. Work through it slowly.'

**•**  Specific mnemonics only: 'Use the acronym MONA to remember...' — tested, real mnemonics

# **QUICK REFERENCE**

## **v3.2 Session Command Reference**

### **Initialization**

| GO | Begin Phase 1 after all 8 settings confirmed |
| :---- | :---- |
| **UPDATE SETTING \[N\]** | Change any Setting 1–8 mid-session |
| **SHOW SETTINGS** | Display current session configuration |
| **RESET SESSION** | Clear all settings, restart Phase 0 |

### **TOC & Research**

| RUN COMPETITOR ANALYSIS | Trigger Phase 4-R1 through R3 |
| :---- | :---- |
| **APPROVE TOC** | Confirm TOC, unlock Phase 4B |
| **REVISE TOC \[instructions\]** | Modify TOC before approval |

### **Digital Companion Handoff (Revised in v3.2)**

| CONFIRM COMPANION PLAN | Lock the Phase 4B-1 shared inputs (test count, questions/test, time limit, readiness score, access code) |
| :---- | :---- |
| **HANDOFF TO SIMULATION FRAMEWORK** | Switch to the KCAPP v3.2 Exam Online Simulation Framework using the locked inputs — see that document's own command reference for all simulator build commands |
| **SHOW LOCKED INPUTS** | Display the current Phase 4B-1 inputs being passed to the simulator build |
| **UPDATE TEST COUNT** | Correct the number of full-length tests if the title/subtitle changes after Phase 4B |

### **Generation**

| GENERATE ALL | Full manuscript front-to-back |
| :---- | :---- |
| **GENERATE FRONT MATTER** | Title page through introduction |
| **GENERATE CHAPTER \[N\]** | Single full chapter with all components \+ image prompts \+ Companion Callout |
| **GENERATE CHAPTERS \[N-M\]** | Chapter range in sequence |
| **GENERATE PART \[N\]** | Full book part/section |
| **GENERATE BACK MATTER** | Conclusion through About the Author |
| **REGENERATE CHAPTER \[N\]** | Re-generate chapter with new instructions |
| **EXPAND SECTION \[name\]** | Add 500–1,000 words to named section |

### **Output & Validation**

| EXPORT DOCX | Compile full manuscript as .docx |
| :---- | :---- |
| **SHOW WORD COUNT** | Current word count and page estimate |
| **SHOW CONTENT SPLIT** | Display current learning-page vs. front/back-matter breakdown |
| **SHOW ANSWER DISTRIBUTION** | Display A/B/C/D count for the in-book Knowledge Check pool |
| **SHOW IMAGE PROMPT LIST** | All embedded image prompts with captions and placement notes |
| **CHECK COMPLIANCE** | Run quality checklist on the current manuscript |
| **SHOW FORMATTING SAMPLE PROFILE** | Display extracted formatting rules from the mandatory sample document |
| **CHECK SYNC** | Confirm the manuscript's stated test count, access code, and simulator URL match what the Exam Online Simulation Framework actually built |

**KCAPP v3.2 — BOOKKIFY PUBLISHING SYSTEM**

*Confidential Internal Use Only | Document 1 of 3 | Knowledge-Centered Adaptive Publishing Protocol*