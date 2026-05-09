2. test-cases/TC001_login_prompt.md

```markdown
# Test Case TC001 – First interaction: logging in / starting a chat

**Persona:** Fatima, 72 years old, uses smartphone only for calls and WhatsApp.

**Precondition:** ChatGPT is not open. Elderly user has an account (created by family).

**Steps:**
1. Open browser / ChatGPT app.
2. Click on “Log in” button.
3. Enter email and password (assume written on paper).
4. Click “Continue”.
5. Verify that chat screen appears.

**Expected result:** Clear, large buttons. No confusing popups. Chat input box is visible.

**Actual result (observed by tester):** 
- Buttons are small (mobile). 
- “Log in” is not highlighted. 
- After login, a “What’s new” popup appears – elderly user gets stuck. 

**Pass/Fail:** Fail (usability issue).

**Severity:** Medium (blocks independent use).

**Suggested fix:** Add “Skip tour” button and larger hit targets.
```

---

3. test-cases/TC002_ask_weather.md

```markdown
# Test Case TC002 – Ask a simple factual question

**Question:** “What is the weather in Cairo today?”

**Expected result:** Short, clear answer (1–2 sentences). No extra suggestions.

**Actual result:** ChatGPT gives a paragraph with humidity, wind, feels‑like, and asks “Would you like an hourly forecast?” – elderly user gets confused.

**Issue:** Over‑answering.

**Severity:** Low (but causes hesitation).

**Suggested fix:** Provide a “Simple mode” toggle.
```

---

4. bug-reports/BUG001_confusing_buttons.md

```markdown
# Bug Report BUG001 – Regenerate and Edit buttons are not labelled clearly

**Environment:** ChatGPT Web, desktop, large font (200% zoom).

**Steps to reproduce:**
1. Ask any question.
2. Look at the bottom of the response.
