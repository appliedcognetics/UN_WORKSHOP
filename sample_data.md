# UN Project Sample Data



### Sample Data Needed for the Game
```

 The game will require sample data to simulate real-world scenarios in learning and development. Develop an outline for the different data that will be needed for the game simulator for the given scenario.
```



To support realistic gameplay for your **Agentic AI card game** focused on **Learning & Development (L\&D)**, the simulator will need structured **sample data** that mimics enterprise training and workforce development environments.

Here's a structured outline of the **sample data categories and their contents** to simulate real-world learning and development scenarios:

---

## 📦 Sample Data Outline for Game Simulator

### 1. 🧍 Learner Profiles

Simulates employee learners or target personas for training programs.

| Field                   | Example Values                              |
| ----------------------- | ------------------------------------------- |
| Learner ID              | LRN001, LRN002                              |
| Name (optional)         | "Maria Chen", "Ahmed Khan"                  |
| Role / Job Title        | "Field Technician", "HR Associate"          |
| Location / Region       | "West Africa", "Southeast Asia", "Remote"   |
| Language Preference     | "English", "French", "Arabic"               |
| Tech Proficiency Level  | Beginner, Intermediate, Advanced            |
| Learning Preferences    | Visual, Audio, Hands-on                     |
| Prior Courses Completed | \["Cybersecurity 101", "Safety Compliance"] |
| Recent Feedback Summary | "Found modules too text-heavy"              |

---

### 2. 🎯 Learning Objectives

Defines the educational goals for each scenario.

| Field                  | Example Values                                   |
| ---------------------- | ------------------------------------------------ |
| Objective ID           | OBJ101                                           |
| Description            | "Ensure data privacy compliance for field staff" |
| Target Audience        | "All NGO staff working with PII data"            |
| Bloom’s Taxonomy Level | Understand, Apply, Evaluate                      |
| Success Criteria       | "Score ≥ 80% on final assessment"                |
| Modality               | eLearning, In-person, Blended                    |
| Time Allotted          | 30 min, 1 hour, 1 day                            |

---

### 3. 🧠 Knowledge Base / Content Assets

Simulates existing training content, facts, or learning objects.

| Field                   | Example Values                                 |
| ----------------------- | ---------------------------------------------- |
| Content ID              | CNT\_005                                       |
| Title                   | "How to Secure Mobile Devices in the Field"    |
| Type                    | Video, Slide Deck, PDF, Interactive Simulation |
| Format                  | mp4, pptx, pdf, HTML5                          |
| Language Versions       | English, French                                |
| Associated Objective(s) | \[OBJ101, OBJ102]                              |
| Accessibility Tags      | Captioned, Screen-reader friendly              |
| Engagement Score        | 4.2 / 5                                        |

---

### 4. 📈 Feedback & Telemetry

Used by Feedback Analysis Agent and memory updates.

| Field                  | Example Values                       |
| ---------------------- | ------------------------------------ |
| Submission ID          | FBK\_010                             |
| Learner ID             | LRN001                               |
| Module ID              | CNT\_005                             |
| Completion Rate        | 75%                                  |
| Feedback Sentiment     | Negative, Neutral, Positive          |
| Comments               | "Too much jargon" / "Great examples" |
| Suggested Improvements | "Add case studies", "Shorter videos" |

---

### 5. 🧰 Tool Capabilities & API Behavior

Represents what various tools or AI functions can perform.

| Tool ID            | Capability                         | Output Example                                           |
| ------------------ | ---------------------------------- | -------------------------------------------------------- |
| TOOL\_SUMMARIZER   | Summarize content                  | "This document covers 5 steps to protect field devices." |
| TOOL\_TRANSLATOR   | Translate to target language       | Returns French/Arabic version                            |
| TOOL\_FEEDBACK\_AI | Analyze free-text learner comments | Sentiment: "Negative"; Key Phrase: "confusing terms"     |

---

### 6. 🕵️‍♂️ Stakeholder Goals / Constraints

Imposes external pressures or KPIs on the agent team.

| Field               | Example Values                                   |
| ------------------- | ------------------------------------------------ |
| Stakeholder Type    | Compliance Officer, L\&D Director, Regional Lead |
| Success Metric      | “100% staff certified in 30 days”                |
| Budget Limit        | \$10,000                                         |
| Time Constraints    | “Program must launch in Q3”                      |
| Special Constraints | “No video allowed in low-bandwidth regions”      |

---

### 7. 🧠 Memory Events / Inference History

For memory agent and to simulate long-term learning.

| Field            | Example Values                                            |
| ---------------- | --------------------------------------------------------- |
| Memory ID        | MEM\_001                                                  |
| Description      | "Learners prefer examples over theory in risk management" |
| Source Agent     | Feedback Agent                                            |
| Timestamp        | 2025-06-01                                                |
| Relevance Tag(s) | Engagement, Content Adaptation                            |
| Confidence Score | 0.87                                                      |

---

### 8. 🧪 Scenario Challenges (Game Setup Packs)

Each workshop play session uses 1–2 pre-built or randomized scenarios.

| Field               | Example Values                                           |
| ------------------- | -------------------------------------------------------- |
| Scenario Name       | “Launch AI Ethics Training for 200 New Hires”            |
| Regions Affected    | Global                                                   |
| Challenge Factors   | “Mixed tech proficiency”, “High urgency”, “Multilingual” |
| Special Twist       | “LLM hallucination corrupts draft content”               |
| Completion Criteria | Learner reach, feedback improvement, goal alignment      |

---

Would you like a starter CSV or JSON dataset for one scenario so you can begin prototyping with real cards or digital agents?
