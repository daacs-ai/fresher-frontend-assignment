# 🚀 Frontend Engineer (0–1 / Fresher) — Hiring Assignment

## **We're Hiring: Junior Frontend Engineer (0–1 Years / Fresher)**

### About Us

DataActions is a venture-backed company headquartered in Singapore, building Decision Agents for Enterprises powered by Causal AI.

#### What You'll Work On

- Building agentic frontend features using React / Next.js
- Turning ambiguous product ideas into clean UI
- Working on reusable components & design systems
- Collaborating closely with product, design & founders
- Learning how real production frontend systems are built

#### What We're Looking For

- Problem-solving mindset as the defacto
- Ability to explain your approach with trade-offs
- Comfort with experimenting (vibe coding)
- Strong fundamentals in JS / HTML / CSS
- Expertise with React & Next.js (and willingness to learn fast)

#### Compensation

=> ₹6-8 LPA + ESOPs

#### How to Apply

**Mail** - thushar.ke@dataactions.ai / cc: adi@dataactions.ai

- Share your GitHub with projects / with demos
- Write a cover letter, why should we hire you?
- No resume is needed

#### How to get shortlisted faster:

Work below problem statement, share your demo repo with a Loom video.

---

Welcome! 👋

This repository contains the frontend hiring assignment for 0–1 year / fresher frontend engineers at DataActions.

**This assignment is designed to evaluate how you think, not how fancy your UI is.**

## 🎯 Purpose of This Assignment

### We are not testing:

- DSA
- Tricky JavaScript questions
- Pixel-perfect UI

### We are testing:

- Your problem-solving approach
- How you break down an unclear problem
- Code structure & clarity
- Ability to explain your decisions
- Comfort with experimenting and iterating (vibe coding 🎧)

## 🧠 Assignment Overview

You'll build a simple **Insight Widget** — a small frontend component that visualizes a metric over time.

Think of it as a mini dashboard card.

## 📌 Core Functional Requirements (Mandatory)

Your app/component should:

- Allow the user to enter:
  - Metric name (text input)
  - Time range → last N days
- Display data for the selected metric and time range
- Data can be mocked / hardcoded
- No backend required
- Visualize the data in any one form:
  - Table
  - Chart
  - List
  - Or any simple creative format
- Update the view when inputs change

## 🧪 Additional Tasks (Choose Any 1–2)

These tasks are optional but strongly encouraged. Pick what interests you — we care more about quality of thinking than completing everything.

### 🔹 Task 1: Insight State Handling

Extend your Insight Widget to handle real-world UI states.

**Requirements:**

- Show a loading state when data is being prepared
- Show an empty state when no data is available
- Show an error state (can be simulated)

**What we're evaluating:**

- How you think about realistic UI scenarios
- State management clarity
- UX awareness

### 🔹 Task 2: Metric Switcher

Add a dropdown or selector to switch between multiple metrics.

**Example metrics:**

- Revenue
- Orders
- Users

Data can still be mocked.

**What we're evaluating:**

- Component reusability
- Clean data flow
- Ability to extend beyond a single use case

### 🔹 Task 3: Make It Reusable

Refactor your widget so it can be reused with different inputs.

**Example:**

```jsx
<InsightWidget metric="Revenue" timeRange={30} />
```

**What we're evaluating:**

- How you design component APIs
- Separation of logic and UI
- Forward-thinking mindset

## 🛠️ Tech Guidelines

- **Framework:** React.js (preferred)
- **Language:** JavaScript or TypeScript
- **Styling:** Anything works (CSS / Tailwind / inline styles)
- **Data:** Mocked or generated locally

⚠️ **Do not over-engineer. Keep it simple.**

## 📁 Suggested Project Structure (Optional)

```
src/
 ├── components/
 │    └── InsightWidget.jsx
 ├── data/
 │    └── mockData.js
 ├── App.jsx
 └── index.js
```

You are free to structure it differently if you have a good reason.

## ✨ What We Care About Most

When we review your submission, we'll focus on:

### 1. Problem-Solving Approach

- How did you interpret the problem?
- Did you make reasonable assumptions?
- Did you keep the solution simple?

### 2. Code Quality

- Readable variable & function names
- Clear component structure
- Logical separation of concerns

### 3. Thought Process

- Why did you choose this UI?
- Why this structure?
- What trade-offs did you make?

### 4. Learning Mindset

- Are you comfortable exploring and iterating?
- Do you explain what you'd improve with more time?

## 🎥 Submission Instructions

You can submit either one of the following:

### Option 1: GitHub Repository

- Push your code to a public GitHub repo
- Include a short explanation in the README:
  - Your approach
  - Assumptions
  - Improvements you'd make

### Option 2: Loom Video (Preferred)

- 5–8 minutes max
- Explain:
  - Your thought process
  - Code walkthrough
  - Trade-offs & future improvements

👉 **UI polish is optional**  
👉 **Clear thinking is mandatory**

## 🚫 What Not To Do

- Don't copy-paste heavy chart libraries just to impress
- Don't over-abstract or build complex architecture
- Don't stress about perfect design

**This is not a trick assignment.**

## ⏳ Time Expectation

**2–4 hours max**

Please don't spend days on this.

## 📩 How to Submit

Send us:

- GitHub repo link or
- Loom video link

via the application form or email shared with you.
