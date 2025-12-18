# 🚀 Frontend Engineer (0–1 / Fresher) — Hiring Assignment

Welcome! 👋

This repository contains the frontend hiring assignment for 0–1 year / fresher frontend engineers at DataActions.

**This assignment is designed to evaluate how you think, not how fancy your UI is.**

## 🌍 About DataActions

DataActions is a venture-backed company headquartered in Singapore, building next-generation Decision Intelligence powered by ontology-driven modelling and Causal AI.

As markets shift toward AI-native operations, competitive advantage no longer comes from static analytics — it comes from the ability to experiment, learn, and decide faster.

DataActions enables that decision and experimentation velocity for supply chain and retail organizations, helping teams move from insight → action with confidence.

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
<InsightWidget
  metric="Revenue"
  timeRange={30}
/>
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

You can submit by doing the following:

### GitHub Repository

- Push your code to a public GitHub repo
- Include a short explanation in the README:
  - Your approach
  - Assumptions
  - Improvements you'd make

### Loom Video

- 5 minutes max
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

**5–6 hours**

Please don't spend days on this.

## 📩 How to Submit

Send us:

- GitHub repo link or
- Loom video link

via the application form or email shared with you.

