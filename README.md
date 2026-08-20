# 🎙️ SVAR Master: Automated Spoken English Evaluation Prep & Simulator

> **A responsive, interactive AI speech evaluation simulator and practice platform for cracking the SHL / Aspiring Minds SVAR Spoken English Assessment.**

---

## 🌟 Overview
**SVAR Master** is a self-contained Single-Page Web Application (SPA) designed to prepare job candidates, ESL learners, and customer service professionals for automated spoken English evaluations like the **SHL / Aspiring Minds SVAR test**.

The simulator replicates the exact 16-minute sequential exam flow, voice prompt synthesis, strict oral answer conventions, and real-time speech-to-text evaluation across **8 comprehensive training chapters** with over 200+ procedurally generated and randomized practice prompts.

---

## 🚀 Key Features

### 1. ⏱️ 16-Minute Full Timed Mock Assessment
* **Authentic Exam Flow:** Sequential test progression through all core SVAR sections with live exam countdown timer.
* **Instant Oral Evaluation:** Real-time speech recognition scoring pronunciation match, cadence, and grammatical correctness.
* **Comprehensive Final Scorecard:** Detailed section-by-section breakdown (A to F), CEFR proficiency rating (A1–C2), and itemized AI feedback.

### 2. 📚 8 Specialized Practice Chapters (200+ Prompts)
* **Chapter 1: Reading Out Loud (40+ Passages):** Pronunciation clarity, rhythm, and elimination of filler pauses.
* **Chapter 2: Sentence Repeat Laboratory (36+ Audios):** Graded one-shot audio memory and affirmative fallback intonation.
* **Chapter 3: Situational & Logical Q&A (32+ Scenarios):** Rapid contextual comprehension and direct answering.
* **Chapter 4: Vocabulary & Collocations (40+ MCQs):** Synonyms and antonyms with strict SVAR oral format verification (*"The answer is [Option], [Word]"*).
* **Chapter 5: Grammar & Structural Accuracy (35+ MCQs):** Subject-verb agreement, tenses, modals, and conditionals.
* **Chapter 6: Extempore Speech Topics Bank (40+ Topics):** 30s prep & 45s speech with domain-specific **Listing Strategy** tips.
* **Chapter 7: Tongue Twisters & Phonetic Gym:** Accent neutralization targeting difficult consonant clusters (`V/W`, `S/SH`, `P/B`, `TH`).
* **Chapter 8: Customer Support Call Roleplay:** Interactive angry/confused customer voice prompts evaluating candidate **Empathy markers** and de-escalation skills.

### 3. 🎲 Anti-Memorization Dynamic Engine
* **Option & Question Randomization:** Multiple-choice options are shuffled on every attempt with dynamic answer-key recalculation to eliminate positional memorization.
* **⚡ Instant Auto-Progression:** Automatically advances to the next question upon answering with an animated progress meter (toggleable ON/OFF).
* **Section Scoreboards:** Real-time round completion modals celebrating progress and logging accuracy.

### 4. 🔒 Persistent Microphone Engine
* **Single-Instance Speech Controller:** Solves browser permission prompts by maintaining an active audio stream and storing permanent grant state in localStorage.
* **Live Audio Visualizer:** Dynamic frequency bar visualizer reflecting mic input levels in real-time.

---

## 🎯 Evaluation Parameters Evaluated
| Metric | Focus | Target Benchmark |
| :--- | :--- | :--- |
| **🗣️ Pronunciation** | Phonetic clarity, syllable articulation, and accent neutralization | &ge; 85% Match |
| **⚡ Fluency & Pace** | Continuous cadence, elimination of dead air (> 2.5s) and stuttering | 110 – 130 WPM |
| **🎶 Intonation** | Affirmative pitch variation and confidence under pressure | Native rise/fall |
| **👂 Listening Comprehension** | One-shot retention and situational logical reasoning | 100% Accuracy |
| **📚 Vocabulary & Grammar** | Precision, correct parts of speech, and strict oral format compliance | Compliant Prefix |
| **🎙️ Extempore Elaboration** | 45-second structured spontaneous discourse using listing techniques | &ge; 30+ Words |

---

## 💻 Tech Stack & Architecture
* **Frontend:** HTML5, Tailwind CSS (Responsive utility layout), Vanilla JavaScript (ES6+ Classes).
* **Audio & Speech APIs:** 
  * `Web Speech API` (`webkitSpeechRecognition` & `SpeechSynthesisUtterance`).
  * `Web Audio API` (`AudioContext`, `OscillatorNode`, and `AnalyserNode` for synthesized tones and mic level meters).
* **Zero Backend Required:** 100% client-side execution — hostable on **GitHub Pages**, **Hostinger**, **Netlify**, or **Vercel** with free automatic SSL/HTTPS.
* **Cross-Device Responsive:** Fully optimized for **Mobile Phones (iOS & Android)**, **Tablets / iPads**, **Laptops**, and **4K Desktop Displays**.

---

## 👥 Who This App Is For
* **Job Applicants:** Candidates appearing for voice assessment rounds in BPO, Tech Support, IT Consulting, and Global MNC hiring drives (Cognizant, Wipro, Genpact, Amazon, Concentrix, Teleperformance, etc.).
* **Call Center Agents:** Professionals seeking to improve de-escalation, empathy, and professional customer phone etiquette.
* **ESL & English Learners:** Anyone aiming to boost spontaneous speaking fluency, neutralize pronunciation quirks, and build extempore confidence.
