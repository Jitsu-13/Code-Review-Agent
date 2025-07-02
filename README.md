# 🤖 Code-Review-Agent

**Code-Review-Agent** is an intelligent AI-powered assistant designed to automate the process of code review. It helps developers identify bugs, optimize code, and follow best practices — saving time and improving software quality.

---

## Overview

Manual code reviews can be time-consuming and subjective. **Code-Review-Agent** leverages AI and static analysis techniques to provide:

-  Fast feedback on code quality
-  Detection of bugs, security vulnerabilities, and smells
-  Enforcement of style guides and best practices
-  Suggestions for improvements

This makes it ideal for solo developers, teams, and open-source contributors.

---

## Features

-  AI-based analysis for intelligent suggestions
-  Static code inspection with customizable rules
-  GitHub integration (planned)
-  Python-first (multi-language support coming soon)
-  Test coverage recommendations
-  CLI or Web-based UI options (depending on implementation)

---



Follow these steps to set up and run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Jitsu-13/Code-Review-Agent.git
cd app
# Create
python -m venv .venv

# Activate (Linux/macOS)
source .venv/bin/activate

# Activate (Windows)
.venv\Scripts\activate

pip install -r requirements.txt


python src/main.py
uvicorn src.main:app --reload
