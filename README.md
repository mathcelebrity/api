# api
MathCelebrity API
# MathCelebrity API

🚀 Instant math problem solving, step-by-step explanations, and quiz generation — powered by the MathCelebrity S.M.A.R.T. algorithm.

---

## 🔗 Official Documentation
👉 https://www.mathcelebrity.com/apidocs.php

---

## ✨ What This API Does

The MathCelebrity API allows developers, platforms, and AI agents to:

- Solve math problems instantly
- Generate step-by-step explanations
- Create randomized quizzes and worksheets
- Support topics from middle school through college

All responses are generated in **under 1 second** using a proprietary pattern-recognition engine.

---

## ⚡ Key Features

- 🧠 **S.M.A.R.T. Algorithm** (Systematic Mathematical Algorithm Reducing Time)
- ⏱️ Sub-second response times
- 📚 Coverage: Algebra, Geometry, Trigonometry, Calculus, Statistics
- 🔄 Randomized quiz generation (500+ calculators)
- 📄 Worksheet + PDF generation
- 🌍 Global usage (students, teachers, edtech platforms)
- 🔐 Secure API key authentication

---

## 🚀 Quick Start

### 1. Get an API Key
Sign up here:
👉 https://www.mathcelebrity.com/apidocs.php

---

## Official SDKs

- JavaScript: https://github.com/mathcelebrity/js-sdk
- Python: https://github.com/mathcelebrity/python-sdk
- PHP: https://github.com/mathcelebrity/php-sdk

## Install Packages
- Node.js: npm install mathcelebrity-sdk
- Python: pip install mathcelebrity
- PHP: composer require mathcelebrity/sdk

### 2. Example Request

```bash
curl https://api.mathcelebrity.com/solve \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d "problem=2x+5=15"

### 3. Sample JSON Response
{
  "problem": "2x + 5 = 15",
  "solution": "x = 5",
  "steps": [
    "Subtract 5 from both sides",
    "2x = 10",
    "Divide both sides by 2",
    "x = 5"
  ]
}

### 4. Core Endpoints
Endpoint	Description
/solve	Solve math problems with steps
/quiz	Generate randomized quizzes
/random	Get random math problems
/anagram	Solve and generate math-related word problems
