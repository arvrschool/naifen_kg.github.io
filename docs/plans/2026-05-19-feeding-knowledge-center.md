# Feeding Knowledge Center Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Create a high-fidelity interactive "Feeding Knowledge Center" HTML that serves as a scientific yet accessible hub for milk powder education, following the "Unreasonable Effectiveness of HTML" design philosophy.

**Architecture:** A single-file interactive dashboard using React (inline via Babel) for portability, Tailwind CSS for styling, and Framer Motion for animations. It will feature age-based feeding guides, a nutrient encyclopedia, and comparison tools.

**Tech Stack:** React 18 (CDN), Tailwind CSS (CDN), Framer Motion (CDN), Lucide Icons (CDN), Recharts (for radar charts).

---

### Task 1: Project Setup & Data Extraction

**Files:**
- Create: `feeding_center/data.js`
- Create: `feeding_center/index.html` (Shell)

**Step 1: Extract data from entities and sources**
Aggregate content from `entities/乳铁蛋白.md`, `entities/OPO结构脂.md`, etc., into a JSON structure in `data.js`.

**Step 2: Initialize index.html with boilerplate**
Include React, Babel, Tailwind, and other necessary CDN links.

**Step 3: Commit**
`git add feeding_center/ && git commit -m "feat: setup feeding center project structure"`

---

### Task 2: Build Interactive Hero & Stage Selector

**Files:**
- Modify: `feeding_center/index.html`

**Step 1: Implement HeroSection**
A high-impact header with a "Science + Love" theme.

**Step 2: Implement StageSelector**
An interactive timeline (0-6m, 6-12m, 1-3y) that filters knowledge cards.

**Step 3: Commit**
`git commit -m "feat: add hero and stage selector"`

---

### Task 3: Nutrient Encyclopedia Matrix

**Files:**
- Modify: `feeding_center/index.html`

**Step 1: Build NutrientMatrix Component**
A high-density grid showing key nutrients, their "Science Mechanism", and "Mom-friendly" explanation. Use a "Card Flip" or "Expandable" interaction.

**Step 2: Integrate Recharts for Radar Chart**
Add a radar chart component to visualize nutrient profiles (Immunity, Digestion, Brain, etc.).

**Step 3: Commit**
`git commit -m "feat: add nutrient matrix and radar charts"`

---

### Task 4: Feeding Q&A and Interactive Tools

**Files:**
- Modify: `feeding_center/index.html`

**Step 1: Add "Science vs Mom" Toggle**
Global toggle to switch the entire page's narrative depth.

**Step 2: Implement Knowledge Cards**
FAQ section with search functionality.

**Step 3: Commit**
`git commit -m "feat: add feeding q&a and interactive tools"`

---

### Task 5: Final Polish & Verification

**Files:**
- Modify: `feeding_center/index.html`

**Step 1: Add Responsive Design**
Ensure the dashboard looks great on both mobile and desktop.

**Step 2: Run verification**
Open in browser (conceptually) and check for errors.

**Step 3: Final Commit**
`git commit -m "feat: finalize feeding knowledge center"`
