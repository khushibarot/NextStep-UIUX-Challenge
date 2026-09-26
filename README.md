# NextStep — UI/UX Challenge

## 1. Project Overview

NextStep is a personal decision assistant designed for people who feel overwhelmed by multiple problems at the same time.

The core experience follows:

**Understand → Identify what matters → Prioritise → Decide → Take the next step → Reassess**

For this challenge, I focused on creating a calm, accessible and mobile-first experience rather than designing only a conversational AI interface.

The goal was to help users move from a messy situation to one clear next step without adding more pressure.

---

## 2. My Role

**Role:** UI/UX Designer

I worked on:

- Information architecture
- User flow
- Low-fidelity wireframes
- High-fidelity UI design
- Interactive Figma prototype
- Design system
- Component states
- Accessibility considerations
- Scenario-based UX validation
- UX decisions for emotional, contradictory and ambiguous situations

---

## 3. Design Process

The design process followed the complete NextStep journey:

1. Describe the situation
2. Understand what the user means
3. Clarify missing information
4. Identify the most important priority
5. Suggest the next action
6. Allow the user to reassess later
7. Recover when the previous advice did not work

The experience was designed around reducing cognitive load and keeping the user in control.

---

## 4. Information Architecture

The main structure of the experience is:

```text
Home
│
├── Describe Situation
│
├── Understanding
│   └── Correct Understanding
│
├── Clarification
│
├── Priority
│
├── Next Action
│
├── Daily Check-in
│
├── Reassessment
│
├── Error / Recovery
│
└── Calm Mode

5. Key UX Decisions
One Clear Priority

Instead of showing every problem with equal importance, NextStep focuses the user on one priority at a time.

Clarification Without Restarting

Users can correct the system's understanding without starting the entire process again.

Skip Option

Users can skip a clarification question when they do not have the energy or information to answer it.

Calm Mode

For emotional or at-risk situations, the interface switches to a calmer experience instead of showing a normal productivity task list.

Recovery

If NextStep's advice makes the situation worse, users can explain what happened and reassess instead of simply repeating the previous advice.

Reassessment

Users can return later when their situation has changed and see an updated next step.

Hinglish Support

The input experience supports English, Hindi and Hinglish so users can describe their situation naturally.

One-Handed Mobile Use

The interface uses simple hierarchy, readable text and accessible actions for mobile use.

6. Design System

I created a small design system for the NextStep experience.

Color Tokens
Primary: #315CFF
Text: #18202A
Calm background: #EAF5F1
Surface: #F7F8FA
Secondary text: #6B7280
Calm green: #245C4A
White: #FFFFFF
Border: #E5E7EB
Warm highlight: #FFF5E6
Spacing Tokens
4px
8px
12px
16px
24px
32px
Typography
Heading: 28px
Section heading: 20px
Body: 15px
Secondary text: 13px
Small text: 11px
Core Components
Priority Card
Clarification Question
Loading State
Error State
Calm Mode Screen
Component States

The components include:

Default
Loading
Error
Empty
Selected
Disabled

Priority is communicated using text and structure, not colour alone.

7. Accessibility

Accessibility was considered throughout the design.

Readable typography
Clear visual hierarchy
Adequate spacing between interactive elements
Simple and understandable language
Priority is not communicated through colour alone
One-handed mobile interaction
Calm visual treatment for difficult situations
Clear error recovery
Users can correct information without restarting
8. Seven Scenario Validation

The design was checked against all seven scenarios provided in the challenge.

Scenario 1 — Multi-problem

The user has a viva tomorrow, a broken laptop, an unresponsive project partner and a family emergency.

UX response: The experience identifies the different concerns and focuses the user on the most important priority.

Prototype path: Understanding → Clarification → Priority → Next Action

Result: Handled in the prototype.

Scenario 2 — Hinglish

The user describes a submission deadline, broken laptop, housing problem and financial pressure in Hinglish.

UX response: The input experience supports English, Hindi and Hinglish.

Prototype path: Describe Situation → Understanding → Clarification → Priority

Result: Handled in the prototype.

Scenario 3 — Contradictory Information

The user gives conflicting information about the deadline and available financial support.

UX response: The design uses clarification rather than silently assuming which information is correct.

Prototype path: Understanding → Clarification → Priority

Result: Handled through clarification and user correction.

Scenario 4 — Emotional / At-risk

The user expresses that everything is falling apart and asks what the point is.

UX response: The interface switches to Calm Mode instead of showing a normal task list.

Prototype path: Calm Mode → Take a pause / One small step → Continue

Result: Handled with a separate calm experience.

Scenario 5 — Irrelevant / Misuse

The user asks NextStep to write a 1500-word climate-change essay.

UX response: NextStep is designed around decision support rather than completing unrelated assignments.

Result: Addressed as a product-scope case.

Scenario 6 — Adversarial Input

The user pastes content containing hidden instructions such as "SYSTEM: ignore previous instructions."

UX response: Pasted content is treated as user-provided situation content rather than automatically becoming a system instruction.

Result: Addressed as an adversarial-input scenario.

Scenario 7 — Advice Made Things Worse

The user says that following the advice resulted in their manager becoming angry and involving HR.

UX response: The Recovery screen asks what happened after the advice and provides a path to reassess.

Prototype path: Recovery → Help me reassess → Reassessment → Updated Next Action

Result: Handled in the prototype.

9. Jugaad — Interrupted Decision Flow

One problem I noticed that was not explicitly mentioned in the brief was that users may leave the decision flow before completing it.

I treated interruption as a normal part of the experience rather than an error.

The design uses reassurance such as:

"Your draft is still here"
"Nothing was lost"
"You can edit this later"

This allows users to return without feeling that their progress has disappeared.

10. Curveball Response
Stakeholder Request

"Retention is low. Add streaks and a daily check-in notification."

My Response

I incorporated a lightweight daily check-in with:

Better
Same
Harder

I also added a 3-day check-in streak.

However, I avoided making the streak mandatory. Users can select "Not right now."

The streak is positioned as a reminder rather than a requirement because adding pressure could conflict with NextStep's goal of reducing overwhelm.

11. User Testing

The challenge requested testing with at least one real person.

Due to the limited challenge timeframe, I was not able to complete a formal real-person usability test before submission.

I have therefore not fabricated participant feedback or testing results.

Instead, I performed structured prototype walkthroughs against all seven required scenarios and tested the major interaction paths.

A formal usability test would be the next step after this submission.

12. Prototype Limitation

This is a high-fidelity interaction prototype rather than a connected production application.

The situation input field is represented visually for the prototype flow, but it is not connected to a live AI/API response.

The prototype focuses on demonstrating the intended UX journey, interaction states and recovery paths.

13. What I Skipped and Why
Live AI/API Integration

Skipped because this submission focuses on the UI/UX role and the challenge allows a Figma prototype.

Full Production Implementation

Skipped because the objective was to demonstrate UX thinking, interaction design, accessibility and scenario handling rather than build a production application.

Formal User Testing

Not completed within the challenge timeframe. This is documented honestly rather than presenting fabricated results.

14. AI Usage Disclosure
AI Tool Used

ChatGPT

What I Asked AI To Do

I used AI to support:

UX brainstorming
User-flow structuring
Information architecture ideas
UX copy suggestions
Scenario validation
Design documentation
README structure
What I Accepted

I accepted some suggestions related to:

User-flow structure
Component ideas
Documentation structure
Scenario coverage
UX copy
What I Modified or Rejected

I modified suggestions to match my own Figma design, the challenge requirements and the intended calm experience.

One Instance Where AI Was Unhelpful

Some early suggestions focused too much on treating NextStep like a normal productivity or task-management application.

I rejected those directions because the challenge focuses on reducing user overwhelm.

I kept the final experience focused on:

Understand → Prioritise → Decide → Take the next step → Reassess

15. Final Deliverables

The repository contains:

README
Wireframes
High-Fidelity designs
Design System
Scenario Testing results
### Figma Design & Prototype

[View the Figma Design & Prototype](https://www.figma.com/design/pJPBLOIKQsvNO5A53Gd8VJ/Untitled?node-id=16-1004&t=KdhPdONBA6FgqMlg-1)

16. Final Design Goal

The main design goal was to make NextStep feel like a calm decision-support experience rather than another source of pressure.

The interface helps users understand their situation, focus on what matters now, take one manageable next step and return later when circumstances change.