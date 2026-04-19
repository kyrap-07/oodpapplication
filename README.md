# ⚖️ T&C Analyzer Pro

A premium, front-end powered **Terms & Conditions Risk Analyzer** that helps users understand what they’re actually agreeing to — in seconds.

---

## 🚀 Overview

T&C Analyzer Pro scans legal text and identifies **potentially risky clauses** using a modular OOP-based architecture.

Instead of forcing users to read long legal documents, it:

* Detects critical clauses (privacy, financial, legal, etc.)
* Calculates a **risk score**
* Highlights dangerous sections
* Explains everything in **plain English**

---

## ✨ Features

### 🔍 Smart Clause Detection

* Identifies patterns like:

  * Data sharing
  * Auto-renewals
  * No refund policies
  * Arbitration clauses
  * Tracking & monitoring

---

### 📊 Risk Analysis System

* Computes a **risk score**
* Categorizes into:

  * ✅ Low
  * ⚠ Medium
  * ⛔ High
  * 🚨 Critical

---

### 🧠 Plain English Explanation

* Converts complex legal language into **human-readable insights**
* Tells users exactly:

  > what the company can do
  > what rights they lose
  > what risks they take

---

### 🎯 Visual UI/UX

* Premium dark/light theme
* Animated risk indicators
* Donut chart for risk breakdown
* Highlighted clauses
* Clean, modern interface

---

### 🧾 History Tracking

* Stores previous analyses using `localStorage`
* Quick reload of past inputs

---

## 🧠 OOP Architecture (Core Concept)

This project is designed to demonstrate strong Object-Oriented Programming principles:

### 🔷 Abstraction

* `BaseAnalyzer` acts as an abstract class
* Defines a common `analyze()` interface

---

### 🔷 Inheritance

All modules inherit from `BaseAnalyzer`:

* `KeywordDetector`
* `RiskAnalyzer`
* `SummaryGenerator`
* `PlainEnglishGenerator`
* `HighlightEngine`

---

### 🔷 Polymorphism

Each class overrides:

```js
analyze()
```

Same method → different behavior depending on class

---

### 🔷 Encapsulation

* Rules, weights, and detection patterns are internally managed
* Logic is modular and isolated per class

---

## ⚙️ How It Works

1. User pastes T&C text
2. `KeywordDetector` finds risky patterns
3. `RiskAnalyzer` calculates score & severity
4. `SummaryGenerator` builds technical summary
5. `PlainEnglishGenerator` explains it simply
6. `HighlightEngine` marks risky phrases
7. UI renders:

   * metrics
   * risk level
   * charts
   * explanations

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (custom design system + themes)
* Vanilla JavaScript
* Canvas API (for charts)
* LocalStorage (for history)

---

## 📱 Responsiveness

* Fully responsive layout
* Works across:

  * Desktop
  * Tablets
  * Mobile devices

---

## 📦 Installation

No setup required.

Just open:

```bash
index.html
```

---

## 🎯 Use Cases

* Quickly reviewing app policies
* Understanding subscriptions before payment
* Educational tool for legal awareness
* Demonstrating OOP in real-world projects

---

## 🔮 Future Improvements

* AI/NLP-based clause detection
* PDF upload support
* Export analysis reports
* User authentication & cloud history
* Multi-language support

---

## 🧑‍💻 Author

Built as a high-impact front-end + OOP demonstration project.

---

## ⭐ Final Note

This is not just a UI project —
it’s a **logic-driven analyzer system** wrapped in a premium interface.

> “Don’t just accept terms. Understand them.”
