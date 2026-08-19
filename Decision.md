# CareerLens — Design Decisions

## 1. Product Direction

CareerLens was designed as a career guidance and skill-readiness landing page focused on helping students understand their fit for a target career role.

The interface emphasizes clarity, visual hierarchy, and a professional dashboard-style product demonstration rather than building a full backend application.

## 2. Visual Design

The design uses a clean, modern interface with:

- A strong hero section and clear value proposition
- A prominent "Analyze My Career" CTA
- A dashboard-style product demonstration
- Skill coverage progress bars
- A recommended next-skill section
- Responsive layouts for desktop and mobile
- Subtle animations and hover interactions

The existing visual direction was preserved during the final polish pass instead of introducing unnecessary redesigns.

## 3. Sample Data

The dashboard uses illustrative sample data to demonstrate how a future career assessment could appear.

Examples include:

- Role match percentage
- Skill coverage percentages
- Recommended skills
- Assessment indicators

These values are explicitly presented as sample/illustrative data and should not be interpreted as real user assessments or statistical claims.

## 4. Interaction Decisions

The landing page focuses on demonstrating the product concept rather than implementing a complete career-analysis platform.

Therefore:

- The primary CTA scrolls to the product demonstration.
- The skill bars animate when the section enters the viewport.
- Navigation links move users to relevant sections.
- Simulated account and activity controls were removed where they could imply functionality that does not exist.

## 5. Accessibility and Responsiveness

The page was designed to work at both:

- 390px mobile width
- 1440px desktop width

Reduced-motion preferences are respected for animations, and the interface avoids intentional horizontal scrolling.

## 6. Technology Choices

The project uses a lightweight frontend implementation with:

- HTML
- CSS
- JavaScript
- Vite
- TypeScript-related configuration and source components

No backend, database, authentication system, external APIs, or unnecessary dependencies were introduced because they were outside the scope of the assignment.

## 7. Final Polish Decisions

The final polish pass focused on improving credibility without changing the core design.

Changes included:

- Labeling dashboard values as illustrative/sample data
- Removing misleading activity and account claims
- Correcting the navigation destination for the "Why CareerLens" section
- Updating the footer year to 2026
- Simplifying non-functional simulated controls
- Preserving the existing CTA
- Preserving the skill-bar animation
- Preserving responsive behavior

## 8. Verification

The final page was checked at 390px and 1440px widths.

The verification confirmed:

- Responsive layout
- No visible horizontal scrolling
- No clipped content
- Skill-bar animation functioning
- No application errors in the browser console
- Successful preview/build behavior
