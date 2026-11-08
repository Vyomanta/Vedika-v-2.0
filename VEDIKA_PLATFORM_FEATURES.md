# Vedika 2.0 — Comprehensive Platform Feature Specification

Vedika 2.0 is an AI-native educational operating system and intelligent Learning Management System (LMS) designed for colleges, universities, and enterprise learning environments. Below is the detailed functional specification of each core capability across the platform.

---

## 1. Hierarchical Course Curriculum Architecture

The academic curriculum is structured into an intuitive, scalable three-tier hierarchy:
$$\text{Course} \longrightarrow \text{Chapters / Modules} \longrightarrow \text{Granular Lessons}$$

### In-Lesson Learning Experience
Each lesson features a rich, interactive learning workspace equipped with integrated AI companions:

* **Ask Vedika (Timeline-Aware Live Video Companion):**
  * A full-duplex conversational voice and text AI tutor integrated alongside the video player.
  * Understands the student’s exact playback timestamp. Students can pause at any point in a lecture and ask questions; Vedika analyzes the active topic and explains difficult concepts with context-sensitive clarity.
  * Supports voice barge-in and real-time sentiment detection to adapt explanations when students feel confused or overwhelmed.

* **Intelligent Personal Study Notes:**
  * **Student Voice Dictation:** Students can dictate personal takeaways in real time using high-fidelity speech-to-text.
  * **AI Auto-Summarization:** With one click, Vedika extracts core principles, equations, and key takeaways from the lesson directly into structured bulleted notes.
  * Notes are securely saved to the student’s persistent profile and can be downloaded or reviewed at any time.

* **Dynamic In-Lesson Q&A & Adaptive Quizzes:**
  * Continuous comprehension checks generated dynamically based on the current lesson material.
  * Provides instant formative feedback, detailed rationale for correct answers, and guidance on related review sections.

---

## 2. Faculty-Managed Course Quizzes

Empowers institutional faculty to author, schedule, and administer rigorous academic assessments directly via the **Organization Admin Portal (`/admin`)**.

* **Faculty Authoring Tools:** Instructors can build custom question banks supporting multiple-choice questions (MCQs), multi-select, and conceptual short answers.
* **Granular Milestone Binding:** Quizzes can be mapped to individual course lessons, chapters, or end-of-course assessments.
* **Flexible Assessment Rules:** Configurable parameters for time limits, passing score thresholds, maximum retry attempts, and randomized question sequences to preserve academic integrity.
* **Automated Scoring & Gradebook Integration:** Instant evaluation upon submission, immediately updating student performance records and cohort gradebook analytics.

---

## 3. Course Assignments & AI-Powered Rubric Evaluation

A comprehensive assignment lifecycle that combines faculty oversight with scalable, automated AI grading.

* **Faculty Assignment Management:**
  * Faculty create assignments with defined submission guidelines, attachment requirements, and deadlines.
  * **Custom Evaluation Rubric Definition:** Instructors specify weighted evaluation criteria in the Admin Panel (e.g., Code Correctness: 40%, Architectural Design: 30%, Documentation & Code Quality: 20%, Edge-Case Handling: 10%).

* **Automated AI Submission Assessment:**
  * When a student submits their assignment (source code, written reports, or design documents), Vedika’s evaluation pipeline assesses the work against the faculty’s exact rubric criteria.
  * Analyzes correctness, logic structure, standards adherence, and syntax accuracy.

* **Faculty Approval & Moderation Loop:**
  * Rather than posting unvetted grades, Vedika compiles a **Comprehensive Assessment Report** for each student submission.
  * Highlights criterion-by-criterion score breakdowns, detailed feedback comments, and identified areas of improvement.
  * Faculty review the AI-generated report, adjust marks or comments if desired, and provide one-click final approval before grades are published to students.

---

## 4. Academic Resources Hub

A centralized, cloud-hosted academic repository providing high-yield supplemental study materials across domains:

* **Curated PDF Digital Library:**
  * Full-text academic textbooks, lecture slides, peer-reviewed research papers, and university reference materials.
  * Indexed by engineering department, subject category, and course module for quick search and preview.

* **Engineered Cheat Sheets:**
  * Concise quick-reference formula sheets for Mathematics, Physics, and Chemistry.
  * High-density syntax and command guides for programming languages (Python, C++, Java, TypeScript) and developer tools (Git, Linux CLI, Docker, SQL).

* **Structured Data Structures & Algorithms (DSA) Roadmap:**
  * Step-by-step interactive learning pathways ranging from foundational data structures (Arrays, Linked Lists, Stacks, Queues, Hash Tables) to advanced paradigms (Trees, Graphs, Dynamic Programming, Greedy Algorithms, Bit Manipulation).
  * Includes recommended problem tiers, complexity cheat sheets, and pattern recognition guides for technical interviews.

---

## 5. Vedika AI Assistant Hub

The central cognitive powerhouse offering four specialized conversational and problem-solving modules:

### 5.1 Ask Vedika (General Academic Tutor)
An all-purpose academic companion providing adaptive, multi-format conceptual explanations:
* **Dynamic Concept Quizzes:** On-demand micro-assessments generated on the fly to test mastery of any subject.
* **Active Recall Flashcards:** Spaced-repetition flashcards designed to accelerate memorization of definitions, formulas, and terminology.
* **Dynamic Infographics & Visual Diagrams:** Real-time generation of visual Mermaid diagrams, flowcharts, hierarchy maps, and state machines directly in the chat interface.
* **Real-World Applied Examples:** Translates abstract theoretical models into concrete industry scenarios and relatable everyday analogies.
* **“Explain Simpler” (Feynman Technique Mode):** Progressively deconstructs dense academic jargon into intuitive, elementary explanations suitable for beginners.

### 5.2 Code with Vedika (Interactive Coding Tutor & Visualizer)
A dedicated computer science programming companion and live execution environment:
* **Interactive Code Visualizer:** Step-by-step visual execution tracking variable mutations, call stacks, heap objects, and pointer references through loop iterations.
* **Live In-Browser Code Runner:** Supports multi-language execution (Python, JavaScript, C++, HTML/CSS) with zero environment setup.
* **Interactive Debugging Katas:** Identifies syntax bugs, runtime exceptions, and logic errors, prompting students with guided Socratic hints rather than simply giving away solutions.
* **Code-Specific Infographics & Explanations:** Visual execution flow diagrams, time/space complexity analysis ($O(n)$, $O(\log n)$), and line-by-line code breakdowns.

### 5.3 Code Puzzle
* A gamified computational thinking arena featuring algorithmic puzzles, code-reordering challenges, and logic-gap problems.
* Reinforces problem-solving resilience, structural syntax comprehension, and debugging efficiency through progressive difficulty levels.

### 5.4 Viva & Technical Interview Simulator
* **Simulated Academic & Industry Panels:** Conducts interactive, verbal or text-based oral examinations (Viva Voce) and professional technical interviews.
* **Dynamic Adaptive Questioning:** Deepens inquiry based on candidate responses, asking follow-up questions to test genuine depth of understanding.
* **Instant Performance Scorecard:** Delivers comprehensive feedback evaluating conceptual depth, technical accuracy, communication clarity, and composure, accompanied by a targeted remediation roadmap.

---

## 6. Vedika Virtual Interactive Labs

Interactive laboratory simulation suites powered by mathematical modeling, physics engines, and PhET simulations that enable risk-free experimentation:

* **Mathematics Lab:**
  * Interactive 2D and 3D coordinate geometry, dynamic calculus visualizers (derivatives as tangent slopes, integrals as accumulated Riemann areas), vector transformations, and matrix operations.

* **Physics Lab:**
  * Virtual experiments in classical mechanics (kinematics, frictionless planes, projectile trajectories, pendulum harmonic motion), electricity & magnetism circuit building, wave optics, and thermodynamics.

* **Chemistry Lab:**
  * 3D molecular structure inspection, dynamic periodic table property trends, stoichiometric reaction balance simulations, acid-base titration curves, and chemical kinetics experiments.

* **Biology Lab:**
  * High-resolution interactive 3D cell organelle exploration, DNA replication and protein synthesis simulations, Mendelian Punnett-square genetics engines, and physiological organ systems walkthroughs.

---

## 7. Jobs & Career Opportunities Portal

An integrated campus placement and career development ecosystem bridging academic excellence with professional opportunities:

* **Curated Job & Internship Board:** Regularly updated engineering, software, and corporate roles tailored for students and fresh graduates.
* **Skill-to-Role Matching:** Evaluates student course completion records, quiz scores, and coding puzzle achievements to highlight aligned job profiles.
* **Direct Application Workflow:** Centralized tracking of applications, interview schedules, job descriptions, and recruiter contact channels.

---

## 8. Student Progress & Cohort Analytics Engine

A centralized intelligence center providing real-time data visibility for students, faculty, and institutional administrators:

* **Personal Student Analytics Dashboard:**
  * Tracks course completion rates, lecture watch milestones, assignment submissions, and quiz performance metrics.
  * Visual competency radar charts illustrating domain strengths, concept mastery, and active learning streaks.

* **Faculty & Institutional Performance Metrics:**
  * Cohort-wide grade distributions, submission punctuality rates, and curriculum bottleneck detection.
  * Early-warning identification of at-risk students who need academic intervention or tutoring reinforcement.
  * Exportable institutional accreditation and performance compliance reports.
