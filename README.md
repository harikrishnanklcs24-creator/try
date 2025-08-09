# Runaway Login Button (The Most Annoying Security Feature Ever) 🎯

## Basic Details
**Team Name:** Junior Mandrake  
**Team Lead:** Harikrishnan K  

---

## Project Description
We built a login page where the button *runs away* when you enter wrong credentials.  
No more boring “Invalid Password” messages — now the button physically escapes your mouse cursor like it owes you money!

---

## The Problem (That Doesn’t Exist)
- **Boring Authentication UX**
- Login screens lack engagement and personality

---

## The Solution (That Nobody Asked For)
We gamified authentication with interactive elements.

**Key Features:**
- ✅ Wrong credentials = button runs away — users must *chase* it to retry
- ✅ Real-time input validation — instant feedback without clicking submit
- ✅ Progressive difficulty — more failed attempts = faster, trickier movement
- ✅ Bot-resistant — moving elements break automated scripts

---

## Technical Details

### Technologies Used
**Frontend:** HTML, CSS, JavaScript (Vanilla) with CSS animations  
**Backend:** None (fully client-side)

---

### Implementation Overview
This is a **client-side interactive login page** with no external dependencies.

**How It Works:**
1. User types credentials → JavaScript checks against hardcoded values
2. On mismatch:
   - Button shakes using CSS transforms
   - Button jumps to a new position based on mouse/touch location
   - Speed & randomness increase with each failed attempt
3. On success:
   - Normal form submission or simulated redirect
4. No server needed — just open `index.html` in a browser

---

## Installation
No installation required.

---

## Run
**Method 1:** Double-click `index.html`  
**Method 2:** Drag `index.html` into any browser  
**Method 3:** Use Live Server in VS Code

---

## Workflow Diagram
![Workflow Diagram](https://github.com/Harikrishnankanjingattu/FUNLOGIN/blob/main/deepseek_mermaid_20250809_fe3e5d.png)

---

## Project Documentation

### Screenshots
![Basic First Login Section](https://github.com/Harikrishnankanjingattu/FUNLOGIN/blob/main/Screenshot%202025-08-09%20013414.png) — Basic first login section

![Error Username and Password](https://github.com/Harikrishnankanjingattu/FUNLOGIN/blob/main/Screenshot%202025-08-09%20013426.png) — Error Username and Password

![Correct Password](https://github.com/Harikrishnankanjingattu/FUNLOGIN/blob/main/Screenshot%202025-08-09%20013514.png) — Correct Password

---

## Project Demo
**Video:** [Runaway Login Button Demo](https://github.com/Harikrishnankanjingattu/FUNLOGIN/blob/main/Screen%20Recording%202025-08-09%20001555.mp4) — This video demonstrates the runaway button in action

**Additional Demos:**  
[GitHub Repo Link](https://github.com/Harikrishnankanjingattu/FUNLOGIN/tree/main)

---

## Team Contributions
- **Harikrishnan K** — Project development & README creation
