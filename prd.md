# Product Requirements Document (PRD)
## Personal Web Profile – Vibe Coding Hackathon

---

## 1. Product Overview

This project is a personal web profile built on top of the **Academic Pages** template.  
It will serve as a central, public-facing hub where visitors can learn who I am, what I do, and explore my work (CV, projects, publications, and contact information).

The web profile should:
- Communicate my personal brand and professional identity.
- Be easy to navigate and understand in a few seconds.
- Support accessibility and multi-modal consumption (text, visual, audio).

---

## 2. Objectives & Success Criteria

### 2.1 Objectives
1. Turn the Academic Pages template into a **personalized, branded web profile**.
2. Provide a **clear entry point** (hero/landing section) that explains who I am and what I do.
3. Offer an **accessible CV** in multiple formats (text, visual, audio).
4. Showcase at least **one interactive paper or portfolio project**.
5. Deploy the site via GitHub Pages (or equivalent) so it is publicly accessible.

### 2.2 Success Criteria
- ✅ All required hackathon milestones are completed and visible on the dashboard:
  - Git linked
  - Academic cloned
  - PRD done
  - Theme done
  - Hero done
  - CV done
  - Paper / Project done
- ✅ A first-time visitor can answer in under 10 seconds:
  - Who is this person?
  - What do they do / study / work on?
  - How can I see their work or contact them?
- ✅ Site is readable and usable on desktop and mobile (basic responsiveness).
- ✅ No obviously broken links or “lorem ipsum” placeholders on key pages.

---

## 3. Target Users & Use Cases

### 3.1 Primary Users
1. **Potential employers / supervisors**
   - Want to quickly understand my skills, background, and experience.
2. **University staff / colleagues / classmates**
   - Want to see my projects, research work, or portfolio.
3. **Professional network / peers**
   - Want a quick overview of who I am and how to connect.

### 3.2 Core Use Cases
1. **View my profile and background**
   - As a visitor, I want to see a short introduction and photo, so I can quickly know who this person is.
2. **Access my CV**
   - As a recruiter or professor, I want to view and download a CV so I can review qualifications in detail.
3. **Explore projects or publications**
   - As a visitor, I want to click into one project or paper and understand the problem, approach, and outcomes.
4. **Contact / connect**
   - As a visitor, I want to see contact links (email, LinkedIn, etc.) so I can reach out.

---

## 4. Scope & Features

### 4.1 In Scope (Hackathon)

**F1 – Custom Theme**
- Update colors, typography, and icon style to reflect my personal brand.
- Implement a light theme as default (dark optional if time allows).
- Theme switcher shows at least three options:
  - Existing light theme
  - Existing dark theme
  - My custom theme

**F2 – Personalized Hero / Landing Page**
- Prominent hero section on the home page that includes:
  - Profile picture or hero image (can be AI-generated).
  - Short tagline (who I am / what I focus on).
  - One–two sentence welcome / value statement.
  - Quick links / buttons (e.g., “View CV”, “See Projects”, “Contact”).

**F3 – Accessible CV (Tri-modal)**
- Text-based CV page optimized for the web (semantic headings, readable layout).
- Visual CV (e.g., infographic, timeline, or storyboard image).
- Audio CV (short recording introducing my background and skills).
- All three formats accessible from a dedicated **CV** page.

**F4 – Interactive Paper or Project Page**
- One dedicated page for either:
  - A publication / paper, or
  - A UX / portfolio project.
- Includes:
  - Title, author(s), affiliation if relevant.
  - Problem statement or abstract.
  - Method / approach section.
  - Results / outcomes.
  - Visual element (image, diagram, or video).
  - Interaction pattern:
    - e.g., hover-to-change image, flip cards, click-to-reveal sections, or scroll-based reveal.
  - Link or button to download full PDF (paper or project report).

---

## 5. Non-Functional Requirements

- **Accessibility**
  - Use proper headings, alt text for images, and good color contrast where possible.
- **Performance**
  - Basic pages should load quickly on a standard connection (no very large uncompressed media files).
- **Maintainability**
  - Content (CV, projects, text) should be in markdown or clear sections so it’s easy to update later.
- **Responsiveness**
  - Layout should be usable on both desktop and mobile (no critical content cut off).

---

## 6. Information Architecture (High-Level)

- **Home**
  - Hero section (photo, tagline, intro)
  - Short highlights (CV, projects, contact)
- **About / Profile**
  - Longer bio, background, interests
- **CV**
  - Web CV + visual CV + audio CV + download link
- **Projects / Publications**
  - List of projects or papers
  - At least one detailed interactive page
- **Contact**
  - Email, LinkedIn, GitHub, and/or other relevant links

---

## 7. Milestones (Mapped to Hackathon Tasks)

1. **Milestone 1 – Git linked**  
   - Repo connected, first commit pushed. ✅

2. **Milestone 2 – Academic cloned**  
   - Academic Pages template added and working in my repo. ✅

3. **Milestone 3 – PRD done**  
   - This document (`prd.md`) created and pushed.

4. **Milestone 4 – Theme done**
   - Custom theme implemented and selectable from theme switcher.

5. **Milestone 5 – Hero done**
   - Personalized landing page with hero section implemented.

6. **Milestone 6 – CV done**
   - CV available in text, visual, and audio formats on a CV page.

7. **Milestone 7 / 8 – Paper / Project done**
   - At least one interactive paper or project page created and linked.

---

## 8. Out of Scope (for Hackathon Timebox)

- Complex backend features or databases.
- Multi-language localization.
- Advanced analytics, login, or user accounts.
- Full design system or component library beyond what is needed for the site.