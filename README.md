# Blaze Calendar Wizard - Product Management Case Study

> **Recruitment Task:** Complete Product Specification for Calendar Widget Configuration Wizard
> **Company:** blaze.tech (Healthcare Low-Code Platform)
> **Author:** Artur
> **Date:** February 2026

---

## 🎯 Quick Start for Reviewers

**New here? Start with these 3 documents:**

1. **[EXECUTIVE_SUMMARY.md](./EXECUTIVE_SUMMARY.md)** - Complete overview (5 min read)
2. **[docs/PRD.md](./docs/PRD.md)** - Full Product Requirements Document (15 min read)
3. **[Miro Board](https://miro.com/welcomeonboard/cndleldYaHpFSU1XLzhRaUFFMTBqTW9lWWtsczJ4MjhzdkRGZXpaYnhuSEJMTTkzQWdaNG5sTjhkUGhzalZFVlBvWUUxWXg1TlEwQzFTWlJBaDlsZTROZ2grcHdHV1Y3eEJQZHRTRGtUbjJtd1FTNzdvZEdqcTN2Um9vTk1lU3R3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=21971845474)** - Visual research workspace

**Time investment:** 20-30 minutes to understand the complete solution.

---

## 📋 Project Overview

### The Challenge

blaze.tech users struggle to configure the Calendar widget - a critical component for healthcare scheduling applications. The current setup requires:
- **20-45 minutes** of manual configuration
- Technical knowledge that non-technical users lack
- No guidance on timezone handling (leading to **25-30% error rate**)
- Trial-and-error approach causing frustration

### The Solution

A **5-step configuration wizard** specifically designed for healthcare use cases that:
- Reduces setup time to **<5 minutes** (88% improvement)
- Eliminates timezone errors (**<5%** target, down from 25-30%)
- Provides medical templates (Patient Appointments, OR Scheduling, Staff Shifts)
- Guides non-technical users with proactive warnings and validation

### Business Impact

| Metric | Before | After (Target) | Improvement |
|--------|--------|----------------|-------------|
| Setup Time | 20-45 min | <5 min | **-88%** |
| Timezone Errors | 25-30% | <5% | **-83%** |
| Completion Rate | 35% | 80%+ | **+129%** |
| Support Tickets | Baseline | -60% | **-60%** |

---

## 🏗️ Methodology & Tools

This project was completed using **Product Builder** - a custom PM workflow automation tool that streamlines the product discovery and specification process.

**Product Builder Repository:** [github.com/Artek338/product-builder](https://github.com/Artek338/product-builder)

### Process

1. **Discovery & Research** (Market analysis, competitive intelligence, user research)
2. **Problem Prioritization** (RICE framework scoring)
3. **Solution Design** (Wizard flow, alternative evaluation)
4. **Requirements Documentation** (PRD, user stories, acceptance criteria)
5. **Validation** (Pain points mapping, edge cases, success metrics)

---

## 📚 Documentation Structure

```
blaze-calendar-wizard/
│
├── 📄 EXECUTIVE_SUMMARY.md          # Complete overview of all deliverables
├── 📄 PROJECT.md                    # Project context and goals
│
└── docs/
    ├── 📊 RESEARCH_REPORT.md        # Market research & competitive analysis
    ├── 🎯 PROBLEM_PRIORITIZATION.md # RICE scoring framework
    ├── 💡 ALTERNATIVE_SOLUTIONS.md  # 5 alternatives evaluated (wizard recommended)
    ├── 🔄 WIZARD_FLOW.md            # 40-page detailed wizard design
    ├── 📋 PRD.md                    # Product Requirements Document (12,000 words)
    ├── 📝 USER_STORIES.md           # 20 user stories (52 story points)
    └── ⚠️ PAIN_POINTS_ANALYSIS.md   # 15 validated user pain points
```

**Total Documentation:** ~80 pages | ~25,000 words

---

## 🎯 Key Findings & Recommendations

### 🔍 Market Gap Identified

**No low-code platform has a calendar-specific configuration wizard:**
- Retool: ❌ No wizard (manual property panel)
- Bubble.io: ❌ No wizard (plugin marketplace)
- OutSystems: ❌ Generic wizard only

**Opportunity:** Differentiate blaze.tech with healthcare-specific calendar wizard.

---

### ⚡ Top Priority Problem: Timezone Handling

**RICE Score: 2400** (2.5x higher than next problem)

- **Why Critical:** Patient care implications (wrong appointment time = missed care)
- **Current State:** 25-30% of calendars have timezone errors
- **Complexity:** Australia has 5 timezone zones during DST
- **Solution:** Proactive Step 2 in wizard - auto-detection, cross-timezone scenarios, DST warnings

---

### 🏆 Recommended Solution: Multi-Step Wizard

**Scored 9.1/10** across evaluation criteria (user fit, problem coverage, differentiation)

**5-Step Flow:**
1. **Use Case Selection** - Medical templates (appointments, resources, shifts)
2. **Timezone Setup** - Auto-detect, cross-timezone handling, Australia DST warning
3. **Date/Time Configuration** - Slots, availability, booking window, buffer time
4. **Display Preferences** - Calendar views, required fields
5. **Preview & Test** - Interactive preview, validation, test booking

**Why This Works:**
- Perfect for non-technical users (primary persona: Kasia - medical coordinator)
- Addresses ALL prioritized problems (timezone, entry barrier, option overwhelm)
- Competitive differentiation (unique to blaze.tech)
- Measurable success metrics

---

## 📊 Impact Summary

### Problems Solved by Wizard

**11 out of 15 pain points addressed (73% coverage)** in MVP scope:

#### ✅ Critical Safety/Adoption (5/5 = 100%)
- Ghost Timezone Configuration (RICE: 2400)
- Timezone Errors in Production (RICE: 1920)
- Overnight Shifts Display (RICE: 800)
- Configuration Paralysis (RICE: 640)
- Setup Dependency/Consultant Factor (RICE: 480)

#### ✅ High-Friction Workflow (5/5 = 100%)
- AI Generator Short-Sightedness (RICE: 360)
- Working Hours Scroll-Trap (RICE: 480)
- Blind "Publish or Pray" Setup (RICE: 384)
- Resource Label Blindness (RICE: 240)
- Walk-in vs Online Booking Conflict (RICE: 300)

#### ✅ Feature Gaps (1/5 = 20%)
- Buffer Time Deficit (RICE: 225)

#### ⏳ Post-MVP (4 gaps deferred - require advanced features)
- Variable Service Duration
- Manual Shift Swap
- OR Block Scheduling
- Recurring Appointments

---

## 🎨 Visual Research Workspace

All research, user interviews, competitive analysis, and design thinking documented on Miro:

**[View Miro Board →](https://miro.com/welcomeonboard/cndleldYaHpFSU1XLzhRaUFFMTBqTW9lWWtsczJ4MjhzdkRGZXpaYnhuSEJMTTkzQWdaNG5sTjhkUGhzalZFVlBvWUUxWXg1TlEwQzFTWlJBaDlsZTROZ2grcHdHV1Y3eEJQZHRTRGtUbjJtd1FTNzdvZEdqcTN2Um9vTk1lU3R3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=21971845474)**

---

## 🚀 Implementation Estimate

**MVP Scope:** 3-4 person-months

- Core wizard: 1-2 months
- Timezone handling: 2 months
- Medical templates: 1 month

**Development Breakdown:**
- 52 story points total
- ~26 dev days (1 developer)
- 3-4 weeks (2 developers with parallelization)

**Priority Epics:**
1. Timezone Configuration (P0 - Critical)
2. Quick Calendar Setup (P0 - Core wizard)
3. Preview & Test (P0 - Error prevention)
4. Accessibility (P0 - WCAG 2.1 AA)

---

## 📖 How to Navigate This Documentation

### For Recruiters/Hiring Managers (15 min)
1. Read [EXECUTIVE_SUMMARY.md](./EXECUTIVE_SUMMARY.md)
2. Skim [docs/PRD.md](./docs/PRD.md) - focus on "Goals" and "Success Metrics"
3. Check [Miro Board](https://miro.com/welcomeonboard/cndleldYaHpFSU1XLzhRaUFFMTBqTW9lWWtsczJ4MjhzdkRGZXpaYnhuSEJMTTkzQWdaNG5sTjhkUGhzalZFVlBvWUUxWXg1TlEwQzFTWlJBaDlsZTROZ2grcHdHV1Y3eEJQZHRTRGtUbjJtd1FTNzdvZEdqcTN2Um9vTk1lU3R3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=21971845474)

### For Product Managers (30 min)
1. Start with [EXECUTIVE_SUMMARY.md](./EXECUTIVE_SUMMARY.md)
2. Deep dive: [docs/PROBLEM_PRIORITIZATION.md](./docs/PROBLEM_PRIORITIZATION.md) (RICE framework)
3. Review: [docs/ALTERNATIVE_SOLUTIONS.md](./docs/ALTERNATIVE_SOLUTIONS.md) (decision rationale)
4. Read: [docs/USER_STORIES.md](./docs/USER_STORIES.md) (implementation ready)

### For Engineers/Architects (45 min)
1. Overview: [EXECUTIVE_SUMMARY.md](./EXECUTIVE_SUMMARY.md)
2. Requirements: [docs/PRD.md](./docs/PRD.md) (full specification)
3. User flows: [docs/WIZARD_FLOW.md](./docs/WIZARD_FLOW.md) (40 pages, detailed)
4. Stories: [docs/USER_STORIES.md](./docs/USER_STORIES.md) (Given-When-Then)

### For UX Designers (30 min)
1. Context: [EXECUTIVE_SUMMARY.md](./EXECUTIVE_SUMMARY.md)
2. User research: [docs/PAIN_POINTS_ANALYSIS.md](./docs/PAIN_POINTS_ANALYSIS.md)
3. Flow design: [docs/WIZARD_FLOW.md](./docs/WIZARD_FLOW.md) (step-by-step UI)
4. Personas: [PROJECT.md](./PROJECT.md) (Kasia & Tomek)

---

## 🔗 Related Resources

- **Product Builder Tool:** [github.com/Artek338/product-builder](https://github.com/Artek338/product-builder)
- **Miro Board:** [Research Workspace](https://miro.com/welcomeonboard/cndleldYaHpFSU1XLzhRaUFFMTBqTW9lWWtsczJ4MjhzdkRGZXpaYnhuSEJMTTkzQWdaNG5sTjhkUGhzalZFVlBvWUUxWXg1TlEwQzFTWlJBaDlsZTROZ2grcHdHV1Y3eEJQZHRTRGtUbjJtd1FTNzdvZEdqcTN2Um9vTk1lU3R3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=21971845474)
- **blaze.tech Platform:** [blaze.tech](https://www.blaze.tech/)
- **Healthcare Solutions:** [blaze.tech/industries/healthcare](https://www.blaze.tech/industries/healthcare)

---

## 💡 What Makes This Work Stand Out

### 1. Data-Driven Prioritization
RICE framework used to objectively prioritize 5 problems - timezone handling scored **2400**, 2.5x higher than next priority.

### 2. Real User Research
10 healthcare professional interviews (doctors, coordinators, nurses, admins) - **validated pain points**, not assumptions.

### 3. Competitive Intelligence
Comprehensive analysis of Retool, Bubble.io, OutSystems - **identified market gap** (no calendar-specific wizard).

### 4. Healthcare Domain Expertise
Medical use cases analyzed (Patient Appointments, OR Scheduling, Staff Shifts) - **templates tailored** to healthcare workflows.

### 5. Implementation Ready
20 user stories with **Given-When-Then** acceptance criteria, 52 story points estimated, **sprint-ready**.

### 6. Accessibility First
WCAG 2.1 AA compliance built into requirements - keyboard navigation, screen reader support.

### 7. Measurable Success
14 KPIs defined with baseline and targets - **time-to-setup: 45min → <5min**, **timezone errors: 30% → <5%**.

### 8. Risk Mitigation
19 edge cases documented - Australia DST, overnight shifts, cross-timezone scenarios, session timeout.

---

## 📄 License

This is a recruitment case study. All documentation is original work created for blaze.tech hiring process.

---

**Questions?** Feel free to reach out for any clarifications or deep dives into specific aspects of the solution.
