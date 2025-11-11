# DiaBuddy UX/UI Graduation Project

![DiaBuddy Cover](Cover.png) <!-- Replace with actual cover image URL from repo -->

## Overview

DiaBuddy is a bilingual (English/Arabic) mobile application designed for diabetes management, awareness, and community support. It targets diabetics, their families/friends, and the general public, built from a survey of 109 participants, patient research, and analysis of apps like mySugr. Key features include CGM-integrated glucose tracking, AI-powered nutrition recommendations, smart reminders, educational videos, and an in-app community to improve health outcomes and reduce stigma.

As of September 2025, the project is in the post-research phase, focusing on user-friendly interface design. This repository contains the full UX/UI deliverables: research artifacts, wireframes, high-fidelity mockups, interactive prototypes (Figma), design system, and presentation materials.

**Project Status:** Ongoing (Review & Testing phase as of November 10, 2025).

### Key Objectives
- Seamless tracking of glucose, meals, and medications.
- Peer support community to combat isolation (65% of users report stress).
- Educational resources to address knowledge gaps (70% unaware of Type 1 vs. Type 2).
- Smart alerts for emergencies and adherence (70% struggle with meal diversity).

## Features
- **Tracking & Monitoring:** Glucose logging with CGM sync, calorie/nutrient auto-tracking, dashboards for trends.
- **Personalization:** AI meal recommendations, customizable reminders.
- **Community:** In-app forums for sharing experiences.
- **Education:** Videos from doctors/nutritionists, bilingual content.
- **Accessibility:** WCAG 2.1 compliant, color-blind friendly design.
- **Bilingual Support:** English/Arabic interface.

## Design System
The DiaBuddy Design System ensures consistency across all UI elements. It's documented in [DiaBuddy Design System - Edited.pdf](https://github.com/pentaRae/DiaBuddy/blob/main/docs/DiaBuddy%20Design%20System%20-%20Edited.pdf) and implemented in Figma.

### Design Philosophy
- **Empathetic & Human:** Soft shadows, rounded corners, gentle animations to reduce cognitive load.
- **Clarity & Simplicity:** Single-purpose cards/inputs; no clutter.
- **Consistency:** Identical patterns for tracking, notifications, social features.
- **Accessibility:** Color-blind palette, scalable fonts, WCAG 2.1 AA contrast.
- **Trust & Motivation:** Micro-interactions (e.g., glucose logging feedback).

### Color System
#### Primary Colors
| Name     | Hex      | Usage                          |
|----------|----------|--------------------------------|
| Green700 | #023728 | Buttons, nav bar, active icons |
| Green500 | #59B35B | Highlights, success, charts    |
| Green300 | #8BD88C | Hover, card backgrounds, tags  |
| Green100 | #D5F2D6 | Info cards, secondary buttons  |

*Gradient for headers:* `linear-gradient(90deg, #023728, #59B35B)`.

#### Neutral Colors
| Name    | Hex      | Usage                          |
|---------|----------|--------------------------------|
| White   | #FFFFFF | Default backgrounds, forms     |
| Gray100 | #F3F4F6 | Cards, containers              |
| Gray200 | #E5E7EB | Disabled buttons/inputs        |
| Gray300 | #D1D5DB | Borders, dividers              |
| Gray500 | #6B7280 | Secondary text/icons           |
| Gray900 | #111827 | Primary text, dark mode        |

#### Functional Colors
| State    | Color    | Usage                          |
|----------|----------|--------------------------------|
| Success  | #16A34A | Task completion, achievements  |
| Error    | #DC2626 | Input errors, critical alerts  |
| Warning  | #F59E0B | Near-threshold sugar, reminders|
| Info     | #3B82F6 | Education cards, alerts        |
| Disabled | #9CA3AF | Inactive elements              |
| Highlight| #FDE68A | Important text/callouts        |

#### Accent Colors
| Accent   | Color    | Use                            |
|----------|----------|--------------------------------|
| Teal500  | #14B8A6 | Graphs, stats indicators       |
| Orange400| #FB923C | Meal visuals, progress meters  |
| Purple500| #8B5CF6 | Challenges, gamification       |
| Pink400  | #F472B6 | Social posts, messages         |
| Cyan300  | #5EEAD4 | Tooltips, hovers               |
| Yellow400| #FACC15 | Warnings, motivational badges  |

### Typography
**Font Family:** Montserrat (Primary) | Tajawal (Arabic).

| Style          | Size | Weight    | Letter Spacing | Case        | UI Placement                  |
|----------------|------|-----------|----------------|-------------|-------------------------------|
| Display/XL     | 48   | Bold      | -0.5%          | Title       | Onboarding titles             |
| Display/LG     | 40   | Semi-Bold | -0.3%          | Title       | Dashboard headers             |
| Heading/H1     | 32   | Semi-Bold | -0.2%          | Sentence    | Page titles (e.g., "My Analytics") |
| Heading/H2     | 24   | Semi-Bold | -0.1%          | Sentence    | Section headers               |
| Heading/H3     | 20   | Medium    | 0%             | Sentence    | Cards, tabs                   |
| Subtitle/Medium| 18   | Medium    | 0%             | Sentence    | Subsections, tooltips         |
| Body/Large     | 16   | Regular   | 0%             | Sentence    | Forms, descriptions           |
| Body/Small     | 14   | Regular   | 0%             | Sentence    | Secondary info                |
| Caption        | 12   | Regular   | 0.5%           | Uppercase   | Helper text, footnotes        |
| Label/Medium   | 14   | Semi-Bold | 1%             | Uppercase   | Form labels, stats            |
| Label/Small    | 12   | Semi-Bold | 1%             | Uppercase   | Units, chart labels           |
| Button/Text    | 16   | Bold      | 1.5%           | Uppercase   | Buttons, CTAs                 |

*Notes:*
- Minimum body size: 16px for readability.
- Arabic/English hierarchy consistent.
- Letter spacing: Slight negative for headers, positive for buttons/labels.
- WCAG 2.1 AA compliant contrast ratios.

### Layout, Grid & Spacing
#### Grid System
| Device         | Columns | Gutter | Margin     | Safe Space              |
|----------------|---------|--------|------------|-------------------------|
| iPhone 16 Pro Max | 4    | 16px  | 24px      | Top 44px - Bottom 34px |
| Tablet         | 8       | 24px  | 32px      | -                       |
| Web            | 12      | 32px  | 64px      | -                       |

*Extra:* Nested grids for cards in dashboards/modals.

#### Radius & Shadows
*Radius:* 16px for rounded corners.

| Shadows  | X    | Y    | Blur  | Spread | Color   | Opacity | Usage                  |
|----------|------|------|-------|--------|---------|---------|------------------------|
| Elevation 1 | 0px | 1px | 3px  | 0px   | #000000| 12%    | Inputs, small buttons |
| Elevation 2 | 0px | 4px | 8px  | 0px   | #000000| 15%    | Cards, panels         |
| Elevation 3 | 0px | 8px | 16px | 0px   | #000000| 20%    | Floating buttons, modals |

## Getting Started

### Prerequisites / System Requirements
- **Hardware:** Any modern device with internet (mobile/desktop for viewing prototypes).
- **Software Dependencies:**
  - Figma

### Installation Steps
1. **Clone the Repository:**
   ```
   git clone https://github.com/pentaRae/DiaBuddy.git
   cd DiaBuddy
   ```

2. **Access Figma Prototype:**
   - Open [Figma Prototype Link](https://www.figma.com/proto/xxxxxx/diabuddy-prototype) (duplicate to your account for editing).
   - Import the Design System file: [Design System Figma](https://www.figma.com/file/yyyyyy/diabuddy-design-system).


### Configuration Instructions
- **Figma Setup:** 
  - Install Montserrat and Tajawal fonts via Figma's font manager.
  - Apply Design System variables (colors, typography) to new components.
- **Bilingual Testing:** Toggle language in prototype settings (English/Arabic layers).
- **Customization:** Edit colors in Figma variables; ensure WCAG compliance via plugin (e.g., Stark).

- **Deployed Version:**
  - Prototype: Click through Figma link for interactive demo (onboarding, logging flows).
- **Demo Video:** Watch [2-min Prototype Walkthrough](https://vimeo.com/xxxxxx/diabuddy-demo) (optional).

## Team
**pentaRae Team:**
- Ahmed Mohamed Eid
- Anas Mohamed
- Rawan Hany
- Darine Mahmoud
- Karma Adnan
- Merola Ashraf
- Ibrahim Sayed

**Instructor:** Badr Sayed

## Testing
- AB Testing was conducted
