**KCAPP EXAM ONLINE**

**SIMULATION FRAMEWORK**

*Knowledge-Centered Adaptive Publishing Protocol*

**VERSION 3.2**

**COMPLETE BUILDABLE SIMULATOR SPECIFICATION**

*40 Rules for a Real, Working, Netlify-Ready Online Exam Practice Centre*

*Document 3 of 3 — Compatible with KCAPP v3.2 Framework and KCAPP v3.2 Instruction Prompt*

Bookkify Publishing System  |  Confidential Internal Use

# **PURPOSE**

This framework is for creating hosted online exam simulations for study guide books. The goal is to create a professional, attractive, exam-style online practice centre that buyers can access through a simple link or QR code.

The simulator must not feel like a basic quiz page. It must feel like a polished digital practice centre with clean design, strong user experience, accurate questions, separate full-length tests, instant scoring, answer keys, detailed explanations, flashcards, checklists, and final readiness tools.

This framework is only for online exam simulations. It is not for:

**•**  Writing the study guide chapters

**•**  Creating the table of contents

**•**  Writing front matter

**•**  Creating title and subtitle options

**•**  Writing book descriptions

**•**  Creating cover copy

**•**  Creating the print Knowledge Check section

## **How This Document Syncs With the Other Two**

| THE THREE-DOCUMENT SYSTEM KCAPP v3.2 Framework governs the manuscript. It hands off to this document at Phase 4B once the title, subtitle, chapter count, target market, and Phase 4B-1 inputs (test count, questions per test, time limit, readiness score, access code) are locked. KCAPP v3.2 Instruction Prompt governs the session workflow — its Step 6 is the exact trigger for following this document's Required Workflow (Rule 6\) to actually build the simulator. This document (KCAPP v3.2 Exam Online Simulation Framework) is authoritative for everything about the simulator itself: design, content, files, and packaging. If anything here seems to conflict with the other two documents on a simulator-specific point, this document wins. |
| :---- |

| SHARED INPUTS FROM THE FRAMEWORK (PHASE 4B-1) Before starting, confirm these locked values from the KCAPP v3.2 Framework's Phase 4B-1: book title and subtitle (for test-count extraction), exam name, year range, target market, number of full-length tests, questions per test, time limit, readiness/passing score, and access code. Do not invent or renegotiate these values inside this document — carry them over exactly. |
| :---- |

# **PART 1 — CORE PRODUCT & DESIGN PHILOSOPHY**

## **1\. Core Product Goal**

The simulator must give the buyer a better experience than simply reading practice questions in a book. The buyer should be able to:

**•**  Scan a QR code or open a simple link

**•**  Enter an access code, if included

**•**  See a professional landing page

**•**  Review a prep checklist before starting

**•**  Choose the full-length practice test they want to take

**•**  Take each test separately, using a timer, moving between questions, and flagging questions for review

**•**  See unanswered questions before submitting, then submit and receive an instant score

**•**  See pass, readiness, or review status, and view section-by-section performance

**•**  Review the answer key and read detailed answer explanations

**•**  Retake a test if needed

**•**  Use flashcards and review tools, and complete a final readiness checklist

The simulator must be useful, attractive, easy to use, and suitable for real exam preparation.

## **2\. Practice-First Design Rule**

The simulator should feel professional and exam-like, but it must not copy the protected design, branding, layout, wording, or interface of an official exam provider. The goal is not to copy the real testing screen — it is a practice-first testing experience that is easier to use, more comfortable, more visually appealing, more guided, and better for learning, reviewing mistakes, and repeated practice.

**•**  Use wording such as: Online Exam Simulation, Practice Test Simulation, Timed Practice Environment, Digital Exam Practice Hub, Online Practice Centre, Exam-Style Practice Centre

**•**  Do not use wording that suggests the simulator is the official exam platform

# **PART 2 — THE DYNAMIC TEST COUNT (MOST IMPORTANT RULE)**

## **3\. Dynamic Full-Length Test Count Rule**

The simulator must follow the exact number of full-length practice tests promised in the book title, subtitle, cover, sales page, or user-provided instructions. Do not automatically create only 3 practice tests.

**•**  If the title or subtitle says "3 Full-Length Practice Tests," create 3 separate tests

**•**  If it says "4," "5," "6," or any other number, create exactly that number of separate full-length tests

**•**  The simulator must adapt its dashboard, test selection page, question sets, timers, answer keys, score reports, saved scores, and restart options to match the required number of tests

Each full-length test must have its own test card, question set, timer, score, answer key, detailed explanations, section breakdown, restart option, and saved score (if browser storage is used).

| NEVER DEFAULT TO 3 The system must not hallucinate that the simulator should always contain 3 tests. The number of tests must be taken from the book title, subtitle, cover promise, or user instructions — carried over from the KCAPP v3.2 Framework's Phase 4B-1. If the title/subtitle and user instructions conflict, follow the user's latest instruction and note the chosen number in the simulator README. |
| :---- |

## **4\. Title and Subtitle Test Count Extraction Rule**

Before planning the simulator, inspect the book title and subtitle carefully. The title/subtitle may include phrases such as: 3 Full-Length Practice Tests, 4 Complete Practice Exams, 5 Timed Practice Tests, 6 Full-Length Mock Exams, 7 Online Practice Tests, 10 Practice Exams. The simulator must match this number exactly.

| EXAMPLE Book title: "Red Seal Painter and Decorator Exam Prep 2027–2028: Study Guide with 5 Full-Length Practice Tests" Required simulator output: Practice Test 1, Practice Test 2, Practice Test 3, Practice Test 4, Practice Test 5 Do not reduce the number to 3\. Do not add extra tests beyond the number promised. Do not create a fixed test structure unless the user has clearly requested that structure. |
| :---- |

If the title/subtitle does not state the number of tests, use the number provided by the user in Phase 4B-1. If neither is available, collect the number before creating the simulator.

# **PART 3 — DEVICE, WORKFLOW & RESEARCH**

## **5\. Device-Friendly Interface Rule**

Every simulator must be designed for mobile phones, tablets, laptops, and desktop screens. This is mandatory. The simulator is for practice, so the design should be comfortable on any device the buyer chooses.

### **Mobile Phone Requirements**

**•**  Single-column layout, large readable text, large touch-friendly buttons, clear answer choices, comfortable spacing

**•**  Easy vertical scrolling, sticky or clearly visible timer, simple question progress display

**•**  A collapsible or scrollable question navigation grid — no cramped side panels, no tiny buttons, no forced horizontal scrolling

### **Tablet Requirements**

**•**  Wider card layout, touch-friendly buttons, comfortable spacing, clear dashboard cards

**•**  Easy question navigation, responsive question map, timer and progress shown clearly, results displayed in readable sections

### **Laptop and Desktop Requirements**

**•**  Full dashboard layout, side question map, large answer cards, visible timer

**•**  Wider review area, score charts or score cards, two-column result layout, better use of screen width

| BEST DESIGN PRINCIPLE Use practice-first design over strict exam-screen copying. The interface should feel serious, but not stressful. It should help the learner practise, review, and improve. |
| :---- |

## **6\. Required Workflow**

The simulator creation process must follow this order:

**1\.**  Identify the exam

**2\.**  Read the book title and subtitle carefully

**3\.**  Extract the required number of full-length tests from the title, subtitle, cover promise, or Phase 4B-1 user instructions

**4\.**  Research the current official exam outline

**5\.**  Build the exam simulation plan

**6\.**  Create the question blueprint

**7\.**  Write the questions

**8\.**  Check for accuracy, uniqueness, and repetition

**9\.**  Create answer keys and explanations

**10\.**  Design the exam-specific interface

**11\.**  Build the hosted-ready simulator files

**12\.**  Test the simulator on mobile, tablet, laptop, and desktop layouts

**13\.**  Check visual quality, colour contrast, and readability

**14\.**  Package the simulator for Netlify Drop or similar static hosting

**15\.**  Provide simple upload instructions

**16\.**  Provide suggested QR code wording for the book

## **7\. Required User Input**

Before creating the simulator, collect or identify — most of this arrives pre-filled from the KCAPP v3.2 Framework's Phase 4B-1:

**•**  Book title | Subtitle, if available | Exam name | Year range

**•**  Number of full-length tests | Number of questions per test | Time limit per test | Passing score or suggested readiness score

**•**  Official exam blueprint or source, if available | Main exam domains | Topic weights, if available

**•**  Special features to include | Brand name, if any | Preferred access code, if any | Preferred colour style, if any

| IMPORTANT TEST COUNT REQUIREMENT The number of full-length tests must be taken from the book title, subtitle, cover promise, or Phase 4B-1 instruction. The simulator must match this number exactly and must not default to 3 unless 3 is the stated number. If the user does not provide the official exam source, look up the current official exam structure before creating the question blueprint. |
| :---- |

## **8\. Official Exam Research Rule**

Before creating questions, the current exam structure must be checked. Use official sources first. Check:

**•**  Official exam provider website | Candidate handbook | Exam blueprint | Occupational standard

**•**  Syllabus | Test plan | Official exam guide | Current exam format | Current topic weights | Recent exam updates

The simulator must be based on the current exam structure. Do not guess the exam format. Do not invent domains. Do not use outdated exam information. If official question style is not public, create original exam-style questions based on the official content outline without claiming they are official questions.

# **PART 4 — PRODUCT STRUCTURE & TEST SEPARATION**

## **9\. Simulation Product Structure**

Each simulator should include:

**•**  Landing page | Access code screen, if used | Dashboard | Prep checklist | Test selection screen

**•**  The required number of full-length practice tests | Timed test interface | Question navigation panel | Flag for review feature

**•**  Unanswered warning before submit | Score report | Section performance breakdown | Answer key | Detailed answer explanations

**•**  Flashcards | Final readiness checklist | Retake option | Mobile/tablet/laptop/desktop-friendly layout | Hosting-ready file package

The number of test options must be generated dynamically based on the required test count: Practice Test 1, Practice Test 2, Practice Test 3, Practice Test 4 — continue until the promised number of full-length tests is reached.

## **10\. Separate Full-Length Test Rule**

The simulator must allow the user to take each full-length test separately. The number of full-length tests must match the number promised in the book title, subtitle, cover, sales page, or user instructions. Do not default to 3 tests unless the title, subtitle, or user instructions clearly state that there are 3 tests.

**•**  Required test options should be generated dynamically: Practice Test 1, 2, 3, 4, 5, 6 — continue the numbering until the required number of full-length tests has been created

Each test must be separate and must include its own questions, timer, score report, answer key, explanations, section performance breakdown, missed-question review, flagged-question review, restart option, and saved score if browser storage is used. The tests must not be merged together unless the user specifically requests a combined practice mode. The dashboard and test selection screen must automatically display the correct number of test cards based on the required test count.

# **PART 5 — QUESTION CREATION & QUALITY**

## **11\. Question Creation Rule**

The simulator must first create the questions before building the interface. Each question must include:

**•**  Question ID | Test number | Domain or topic | Difficulty level | Question stem

**•**  Four answer choices, unless the exam uses another format | Correct answer | Detailed explanation | Reason why the correct answer is right

**•**  Short reason why the other options are wrong, if useful | Source topic or blueprint reference | Skill tested | Keyword tags

The questions must be written as original exam-style questions. Do not copy official exam questions. Do not copy competitor questions. Do not write vague or weak questions. The question count must match the required number of tests, the required number of questions per test, and the official exam blueprint or best available topic outline.

| EXAMPLE If the book promises 5 full-length tests and each test has 100 questions, the simulator must contain 500 total questions. |
| :---- |

## **12\. No Repetition Rule**

The simulator must avoid repetition across all tests. Do not repeat the same question wording, the same answer pattern, the same scenario with only small wording changes, the same correct answer explanation, the same tested fact too many times, or the same distractor style too often. Each practice test should feel fresh. A topic may appear in more than one test if it is important, but the question angle must be different.

| Poor Repetition | Test 1 asks what primer does. Test 2 asks the same thing with different wording. Test 3 asks the same thing again. |
| :---- | :---- |
| **Better Approach** | Test 1 asks about primer purpose. Test 2 asks about choosing primer for a stained surface. Test 3 asks what can happen when primer is skipped on a porous surface. |

## **13\. Difficulty Balance Rule**

Each test should include a realistic mix of difficulty levels. Suggested balance: 30% easy recall, 50% moderate application, 20% difficult scenario or judgement questions. For trade and professional exams, the questions should not be too simple.

**•**  The simulator should include: knowledge questions, process questions, safety questions, scenario-based questions

**•**  application questions, troubleshooting questions, common mistake questions, best action questions, material or tool selection questions, and interpretation questions where relevant

## **14\. Blueprint Weighting Rule**

The questions must match the official exam weighting as much as possible. If the official blueprint says a domain is worth 25% of the exam, about 25% of each practice test should cover that domain.

**•**  If no official weights are available, assign question space based on: importance in the exam outline, frequency in the trade or subject, difficulty for learners, core safety or professional importance, and competitor topic coverage without copying competitor content

The question distribution should be documented in the README or question audit file.

# **PART 6 — SCORING, FEEDBACK & STUDY TOOLS**

## **15\. Answer Key and Explanation Rule**

Answer keys and explanations must be shown only after the test is submitted. During the test, the user should not see correct answers, explanations, hints, or scores.

**•**  After submission, the user should see: total score, percentage score, pass or readiness status, correct answer for every question, the user's selected answer, detailed explanation, topic or domain for each question, section score breakdown, questions missed, and questions flagged

The answer explanation should help the learner understand, not just reveal the answer.

## **16\. Score Report Rule**

The score report must be clear and motivating. It should include:

**•**  Total questions | Correct answers | Incorrect answers | Unanswered questions | Percentage score

**•**  Suggested readiness level | Domain-by-domain performance | Weak areas to review | Strong areas | Retake recommendation

| 85% and above | Strong Readiness |
| :---- | :---- |
| **70–84%** | On Track |
| **50–69%** | Needs Review |
| **Below 50%** | Study Again Before Retesting |

If the official passing score is known, use it carefully as a reference. If the official passing score is not known, use "readiness score" instead of "passing score."

## **17\. Prep Checklist Rule**

The prep checklist should appear before the test is taken. The checklist helps the buyer feel guided and prepared. It may include:

**•**  I understand the test time limit. | I have reviewed the main exam topics. | I can sit without distractions.

**•**  I have reviewed key terms. | I have reviewed safety or core rules. | I understand how scoring works.

**•**  I am ready to take the test in one sitting. | I will review explanations after submission. | I will mark weak areas after the test. | I will retake the test after reviewing mistakes.

The checklist should be specific to the exam when possible. For example, a Red Seal Painter and Decorator checklist should mention safety and PPE, surface preparation, coatings, wall coverings, wood finishing, product labels, and safety data sheets.

## **18\. Flashcard Rule**

Flashcards should be included as a learning tool, not as a replacement for the tests. Flashcards should cover:

**•**  Key terms | Definitions | Safety concepts | Common mistakes | Formula or rule reminders | Process steps | Important differences | High-yield facts

Each flashcard should have a front side, back side, and topic tag. Flashcards should be short, clear, and useful for quick review.

# **PART 7 — VISUAL DESIGN**

## **19\. Interface Design Rule**

The simulator must be graphically appealing and matched to the exam type. The design should not use random colours. The visual theme should match the exam, trade, profession, or subject.

| Trade Exams | Deep navy, slate grey, safety orange, tool yellow, steel blue. Clean workshop style, practical cards, strong buttons, clear progress indicators, subtle tool/material design cues. |
| :---- | :---- |
| **Painter and Decorator Exams** | Paint-swatch inspired: deep blue or charcoal base, warm accents, clean white panels, soft gradients. Professional trade studio feel, paint sample cards, colour strip accents, calm but practical layout. |
| **Health Exams** | Calm blue, white, soft green, light grey. Clean clinical environment, calm and trustworthy, easy to read, low stress. |
| **Technology Exams** | Dark navy, electric blue, purple, soft black, light grey. Modern dashboard, clean data cards, progress bars, digital testing interface. |
| **Education Exams** | Blue, green, warm yellow, soft white. Friendly study environment, clear cards, less intimidating, easy navigation. |

## **20\. Visual Quality and Readability Upgrade Rule**

Every online exam simulator must be designed as a polished, modern digital practice centre, not as a basic quiz page. The interface must be visually appealing, creatively designed, and professionally presented. It should feel like a valuable online study product that buyers are happy to access from a book QR code.

### **Do Not Create**

**•**  A basic white page with simple buttons, or a plain quiz layout with little styling

**•**  Random colour combinations, low-contrast text, white text on white or very light backgrounds, dark text on dark backgrounds

**•**  Busy backgrounds that make text hard to read, tiny buttons or cramped spacing

**•**  A layout that feels like a school worksheet instead of an online practice centre

### **The Design Must Include**

**•**  A strong hero or welcome section, attractive dashboard cards, clear test cards, smooth visual hierarchy

**•**  Themed colour palette, high-contrast text, readable answer choices, professional buttons

**•**  Progress indicators, score cards or score rings, domain performance bars, clean spacing

**•**  Mobile-friendly visual flow, tablet-friendly card layout, laptop and desktop dashboard layout

| CONTRAST RULES — NON-NEGOTIABLE Never use white text on a white, cream, pale grey, pale yellow, or very light background. Never use dark text on dark navy, black, charcoal, or deep colour backgrounds. If the background is dark, use light text with strong contrast. If the background is light, use dark text with strong contrast. Buttons must have clear text contrast. Cards must use readable text colours. Answer options must remain easy to read before and after selection. Correct and incorrect answer states must remain readable. Selected answer choices must not reduce text visibility. |
| :---- |

The simulator must feel serious, modern, and engaging without being distracting. The goal is a clean, seamless, interactive study experience that feels better than reading practice questions in a book.

## **21\. Enhanced Graphical Appeal Rule**

The simulator must look and feel like a professionally designed online practice centre. It must not look like a basic quiz, plain webpage, or unfinished HTML project. Each simulator should use an exam-specific visual identity with thoughtful colour choices, modern spacing, clear cards, polished buttons, visual progress indicators, and a smooth test-taking flow.

**•**  A visually strong landing page, a professional dashboard, attractive practice test cards, interactive checklist sections

**•**  A focused timed test screen, clear answer choice cards, flag-for-review controls, a question navigation map

**•**  A polished score report, domain performance visuals, answer explanation cards, flashcard review cards, final readiness tools

Users should always understand where they are, what test they are taking, how much time remains, how many questions are complete, which questions are unanswered or flagged, and what to do next.

### **Visual Hierarchy**

**•**  Primary actions should stand out; secondary actions should be visible but less dominant

**•**  Warnings should be noticeable without feeling alarming; results should feel rewarding and useful; review sections should be easy to scan

### **Creative but Controlled Elements**

**•**  Subtle gradients, soft background patterns, professional card shadows, section icons, accent colour strips, progress bars, score rings, status badges, themed decorative details related to the exam

Do not overload the page with decoration. The design should be creative, but the learner's focus must remain on practising, answering, reviewing, and improving. The final interface must be checked on mobile, tablet, laptop, and desktop to confirm that it looks polished on every screen size.

## **22\. User Experience Rule**

The simulator must be easy and enjoyable to use. The user experience should include:

**•**  Clear start button, simple instructions, test choice screen, timer always visible or easy to find, question number always visible

**•**  Progress bar, question navigation grid, flag for review option, saved score in browser storage if possible

**•**  Warning before submitting unanswered questions, smooth movement between questions

**•**  Mobile/tablet/laptop/desktop-friendly layout, clear score page, clear answer review page, retake button, back to dashboard button

### **Avoid**

**•**  Cluttered pages, tiny text, too many colours, confusing buttons, hidden navigation, slow interactions

**•**  Overly playful design that weakens exam seriousness; layout that works only on desktop or is hard to use on a phone; any colour combination that makes text difficult to read

# **PART 8 — SCREEN-BY-SCREEN REQUIREMENTS**

## **23\. Test-Taking Flow**

The test flow must follow this order:

**1\.**  Landing page

**2\.**  Access code screen, if used

**3\.**  Dashboard

**4\.**  Prep checklist

**5\.**  Test selection

**6\.**  Test instructions

**7\.**  Start test

**8\.**  Timed question screen

**9\.**  Review flagged or unanswered questions

**10\.**  Submit confirmation

**11\.**  Score report

**12\.**  Answer key and explanations

**13\.**  Weak area review

**14\.**  Retake or return to dashboard

## **24\. Dashboard Requirements**

The dashboard should show:

**•**  Book or exam title | Welcome message | One card for each full-length practice test

**•**  Flashcards card | Prep checklist card | Final readiness checklist card | User's saved scores, if browser storage is used | Short instruction text

Each test card should show: test name, number of questions, time limit, status (Not Started / Completed / Retake), last score if available, and a start button. The number of test cards must match the required number of full-length tests.

| EXAMPLE If the book promises 5 full-length practice tests, the dashboard must show 5 separate test cards. Do not show only 3 test cards unless the required test count is 3\. |
| :---- |

## **25\. Test Screen Requirements**

The test screen must include:

**•**  Exam title | Test number | Timer | Question number | Progress bar | Question text | Answer options

**•**  Previous button | Next button | Flag for review button | Question navigation grid | Submit button | Unanswered question warning

The layout should feel focused and serious. On mobile, the question navigation grid may appear below the question or in a compact collapsible section. On laptop and desktop, it may appear as a side panel. The test screen must remain readable, polished, and comfortable on every device.

## **26\. Results Screen Requirements**

The results screen must include:

**•**  Score percentage | Correct count | Incorrect count | Unanswered count | Readiness level

**•**  Domain performance chart or bars | Weak topic list | Strong topic list | Answer key | Detailed explanations | Retake button | Return to dashboard button

The score report should feel rewarding and useful, not plain or boring. Use score cards, a score ring or strong visual score block, domain performance bars, clear missed-question review, motivating readiness language, and clean explanation cards.

## **27\. Accessibility Rule**

The simulator should be easy for most users to access. Use:

**•**  Large readable text, strong colour contrast, keyboard-friendly buttons, clear labels

**•**  Mobile/tablet/desktop responsive design, simple navigation

**•**  No required download, no required app installation, no complicated login, no hidden instructions

The buyer should not need technical knowledge to use the simulator.

# **PART 9 — HOSTING, ACCESS, AND FILE STRUCTURE**

## **28\. Hosted Access Rule**

The simulator should be built as a static website that can be hosted through Netlify Drop or a similar static hosting service. The buyer should not need to download files. The final hosted experience should be:

**1\.**  QR code in book leads to hosted page

**2\.**  The page opens in browser

**3\.**  The buyer uses the simulator immediately

**Recommended hosting method:**

**1\.**  Build the simulator as HTML, CSS, and JavaScript

**2\.**  Package the files into a folder or zip file

**3\.**  Upload to Netlify Drop

**4\.**  Copy the live Netlify link

**5\.**  Create a QR code from the link

**6\.**  Add the QR code to the book

## **29\. Access Code Rule**

A simple access code may be used. The code should be printed inside the book.

| EXAMPLE Access Code: PAINTER2027 |
| :---- |

The access code should not make the buyer create an account. The access code should only add light protection. Do not make the buyer go through a stressful sign-up process. The access code screen should look professional and match the simulator theme — it should not look like a plain password form.

| SYNC WITH THE FRAMEWORK This is the same access code locked in the KCAPP v3.2 Framework's Phase 4B-1. Use it exactly as confirmed there — do not generate a different code independently, and report back to the manuscript workflow if it changes. |
| :---- |

## **30\. File Structure Rule**

The final simulator package should include:

| REQUIRED FILE STRUCTURE exam-simulator/   index.html   style.css   script.js   questions.js   README.txt   question-audit.csv   qr-code-book-page-copy.txt |
| :---- |

Optional files: logo image, icon folder, brand assets, QR instruction page, extra documentation, theme assets.

The simulator should be Netlify-ready. The user should be able to upload the folder or zip file and receive a live hosted link.

## **31\. Question Data Structure**

Each question should be stored in a clear structure. Example format:

| QUESTIONS.JS FORMAT {   id: "T1-Q001",   test: 1,   domain: "Surface Preparation",   difficulty: "Moderate",   question: "Question text here",   options: \["Option A", "Option B", "Option C", "Option D"\],   answer: 1,   explanation: "Detailed answer explanation here.",   whyOthersAreWrong: \[     "Option A is wrong because...",     "Option C is wrong because...",     "Option D is wrong because..."   \],   sourceTopic: "Official blueprint topic or exam domain",   skillTested: "Skill or knowledge area tested",   tags: \["surface preparation", "adhesion", "coatings"\] } |
| :---- |

The test number must match the correct practice test: Test 1 questions use test: 1, Test 2 questions use test: 2, and so on until the required number of tests is reached.

# **PART 10 — QUALITY CONTROL**

## **32\. Quality Control Before Building the Page**

Before building the simulator, check that:

**•**  The number of tests matches the title, subtitle, or user instruction

**•**  The number of questions per test is correct

**•**  All questions are unique; no question is repeated across tests

**•**  Correct answers are accurate; answer choices are clear; distractors are believable

**•**  Explanations are useful; difficulty is balanced; domains match the exam blueprint

**•**  Question wording is clear; no answer pattern is too obvious; no question gives away another answer

**•**  No official copyrighted question is copied; no competitor question is copied

**•**  No explanation is too short; no topic is overused; no key topic is missing

## **33\. Quality Control After Building the Page**

Before delivery, test the simulator. Check that:

**•**  Access code works, if used; dashboard opens; prep checklist works

**•**  The correct number of full-length tests appears; each test starts separately with its own timer, question set, and score report

**•**  Timer works; questions display correctly; options can be selected

**•**  Previous and Next buttons work; flag for review works; question navigation works; submit warning works

**•**  Score calculation is correct; answer key is correct; explanations display correctly; section breakdown is correct

**•**  Retake works; back to dashboard works; flashcards work

**•**  Mobile, tablet, laptop, and desktop layouts all work; no horizontal scrolling appears on mobile

**•**  Text is readable on small screens; buttons are easy to tap

**•**  Netlify upload package is ready

## **34\. Visual QA and Contrast Testing Rule**

Before packaging the simulator, perform a visual quality check. Confirm that:

**•**  The simulator does not look basic or generic; the landing page looks professional

**•**  The dashboard feels like a polished practice centre; the test screen is clean and focused

**•**  The results screen is visually useful and motivating

**•**  Text is readable on every background; no white text on a white or very light background; no dark text on a dark background

**•**  Buttons have strong contrast; answer choices are easy to read; selected answers remain readable

**•**  Correct and incorrect answer states are clearly visible

**•**  Mobile layout does not feel cramped; tablet layout feels like a study app; laptop and desktop layout uses space professionally

**•**  The overall experience feels seamless, interactive, and buyer-friendly

| IF ANYTHING FAILS If any part of the simulator looks plain, unfinished, hard to read, or visually weak, redesign that section before delivery. |
| :---- |

# **PART 11 — PACKAGING & DELIVERY**

## **35\. Final Output Package**

The final output should include:

**•**  A Netlify-ready zip file with all website files; all questions included in questions.js

**•**  README upload instructions; suggested QR code page wording; suggested access code, if used

**•**  Question audit file; short note listing simulator features

The package must be ready for static hosting. The user should not need to manually assemble the files.

## **36\. README Requirements**

The README should include:

**•**  Simulator name | Exam name | Year range | Number of full-length tests included | Questions per test | Total number of questions

**•**  Time limit per test | Readiness score or passing score reference | Access code, if used

**•**  Hosting instructions | Netlify Drop upload steps | Reminder to test on mobile, tablet, laptop, and desktop

**•**  Question blueprint summary | Domain distribution summary | Notes about originality of questions

The README must clearly document the exact number of tests created.

## **37\. QR Code Book Page Copy Rule**

The simulator package should include suggested QR code wording for the book, matched to the exam and the number of practice tests included.

| EXAMPLE COPY Access Your Online Exam Simulation Scan the QR code or visit the link below to open your digital practice centre. Inside, you can take the full-length timed practice tests, review your score instantly, study detailed explanations, use flashcards, and complete a final readiness checklist. Access Code: PAINTER2027 |
| :---- |

Example for 5 tests: "This online practice centre includes 5 full-length timed practice tests, instant scoring, detailed answer explanations, flashcards, and final readiness tools." Do not say 3 tests if the book promises a different number.

| SYNC WITH THE FRAMEWORK This exact copy — or a close variant of it — is what gets printed on the KCAPP v3.2 Framework's front-matter 'How to Access Your Digital Companion' page, the Companion Callout boxes, and the Companion Access Card. Hand this text back to the manuscript workflow once finalized. |
| :---- |

## **38\. Unique Selling Point Rule**

Each simulator should have a clear unique selling point based on the exam. The unique selling point should guide the page design, wording, features, and subtitle language.

| Red Seal Trade Exams | A trade-focused online practice centre with full-length timed tests, job-site scenarios, safety review, tool and material questions, detailed explanations, flashcards, and readiness checklists. |
| :---- | :---- |
| **Health Exams** | A calm online practice centre with patient-care scenarios, safety checks, timed tests, answer explanations, flashcards, and weak-area review. |
| **Technology Exams** | A modern online test lab with timed exams, scenario questions, troubleshooting practice, score tracking, section breakdowns, flashcards, and readiness review. |
| **Education Exams** | A friendly online study hub with timed practice, simple explanations, score tracking, flashcards, and last-week review support. |

# **PART 12 — FINAL RESPONSE & GUIDING PRINCIPLE**

## **39\. Final Response Rule**

When the simulator is created, the response should be short. It should include:

**•**  Download link for the Netlify-ready zip file

**•**  Access code, if used

**•**  Quick upload instruction

**•**  Reminder to test the live link after upload

| EXAMPLE FINAL RESPONSE Done. I created the Netlify-ready online exam simulator with 5 separate full-length practice tests. Download: \[file link\] Access code: PAINTER2027 Upload the zip file to Netlify Drop. Netlify will give you a live link. Test the link on mobile, tablet, laptop, and desktop before turning it into a QR code for the book. |
| :---- |

If the simulator contains more than 3 tests, always mention the correct number.

## **40\. Final Rule**

The simulator must be more than a quiz. It must be a polished online exam practice experience. It must combine:

**•**  Accurate exam-style questions and the exact number of full-length tests promised by the title, subtitle, or user instruction

**•**  Separate timed test experiences, clear answer keys, detailed explanations

**•**  Professional exam-like interaction, attractive exam-specific design, strong colour contrast, creative and polished visual presentation

**•**  Prep checklist before testing, flashcards and review tools, instant scoring, section breakdowns

**•**  Easy hosted access, mobile/tablet/laptop/desktop-friendly design

**•**  A buyer-friendly experience that feels valuable

| THE THREE THINGS THIS FRAMEWORK MUST NEVER DO It must never default to 3 tests unless 3 is the stated number. It must never use unreadable colour combinations. It must never look like a basic quiz page. |
| :---- |

The final product should feel like a professional, interactive, seamless online exam practice centre.

# **QUICK REFERENCE**

## **Simulator Build Command Reference**

| BUILD SIMULATOR | Run the full Required Workflow (Rule 6\) using the locked Phase 4B-1 inputs from the KCAPP v3.2 Framework |
| :---- | :---- |
| **SHOW LOCKED INPUTS** | Display the test count, questions/test, time limit, readiness score, and access code currently in use |
| **SHOW QUESTION AUDIT** | Display the question-audit.csv summary: domain distribution, difficulty balance, per-test counts |
| **RUN PRE-BUILD QA** | Execute the Rule 32 checklist before writing interface code |
| **RUN POST-BUILD QA** | Execute the Rule 33 and Rule 34 checklists before packaging |
| **PACKAGE FOR NETLIFY** | Assemble the Rule 30 file structure into a Netlify Drop-ready folder or zip |
| **SHOW README** | Display the generated README.txt content |
| **SHOW QR COPY** | Display the generated qr-code-book-page-copy.txt content for handoff to the manuscript |

| REMEMBER This document owns every simulator-specific decision. The KCAPP v3.2 Framework and Instruction Prompt hand off to this document at the right moment and pick back up once a live URL, access code, and QR copy are confirmed. Keep all three documents' shared facts — title, subtitle, test count, access code, target market — identical across every session. |
| :---- |

**KCAPP v3.2 EXAM ONLINE SIMULATION FRAMEWORK — BOOKKIFY PUBLISHING SYSTEM**

*Confidential Internal Use Only | Document 3 of 3 | Compatible with KCAPP v3.2 Framework and Instruction Prompt*