# Product Requirements Document (PRD)
**Project:** Wise Builder Resume Portfolio Site  
**Project #:** 1  
**Author:** Tanya Turitto  
**Status:** Shipped ✅  
**Version:** 1.0  
**Last Updated:** March 2026  

---

## 1. Problem Statement

Job seekers in product management and AI roles need a way to demonstrate 
skills beyond a traditional resume. A static Word document cannot showcase 
technical fluency, accessibility awareness, product thinking, or the ability 
to build and ship real products.

**The problem:** Tanya Turitto had no public-facing proof of her ability to 
think like an AI PM and build real digital products.

---

## 2. Goal

Build and ship a professional portfolio site that:
- Lives at a custom domain (wisebuilder.me)
- Demonstrates WCAG 2.1 AA accessibility compliance
- Is fully documented like a real product
- Is version controlled and managed via GitHub Projects
- Serves as Project #1 in a growing AI PM portfolio platform

---

## 3. Users & Personas

| Persona | Who They Are | What They Need |
|---------|-------------|----------------|
| Hiring Manager | Recruiter or PM lead reviewing candidates | Quick proof of skills, live work sample, easy to navigate |
| Technical Interviewer | Engineer or technical PM | Code quality, accessibility, decision rationale |
| Networking Contact | Fellow PM or industry peer | LinkedIn-shareable link, professional first impression |

---

## 4. Success Metrics

| Metric | Target | Status |
|--------|--------|--------|
| Site live at custom domain | wisebuilder.me | ✅ Done |
| WCAG 2.1 AA compliant | All criteria pass | ✅ Done |
| Mobile responsive | Works on all screen sizes | ✅ Done |
| Dark mode toggle | Persists across sessions | ✅ Done |
| GitHub repo public | Visible to hiring managers | ✅ Done |
| Project board active | Backlog / In Progress / Done | ✅ Done |
| Documentation complete | PRD, Infra, Flowchart, Retro | 🔄 In Progress |
| Lighthouse score | Target 90+ all categories | 📋 Backlog |
| Google Analytics | Visitor tracking active | 📋 Backlog |

---

## 5. Scope

### In Scope (v1.0)
- Single page HTML/CSS/JS site
- Sections: Hero, About, Certifications, Experience, Education, Contact
- Light / dark mode toggle
- WCAG 2.1 AA accessibility
- Custom domain via Porkbun + GitHub Pages
- Professional email via Cloudflare routing
- Full product documentation
- GitHub Projects board

### Out of Scope (v1.0 — considered for v2)
- Contact form
- Google Analytics
- Projects showcase page
- Blog or case study section
- CMS or database

---

## 6. Technical Requirements

| Requirement | Detail |
|-------------|--------|
| No framework | Plain HTML/CSS/JS only |
| No build step | Single index.html file |
| Hosting | GitHub Pages — free |
| Accessibility | WCAG 2.1 AA — all criteria |
| Performance | No external dependencies except Google Fonts |
| Browser support | All modern browsers |
| Mobile | Fully responsive via CSS Grid/Flexbox |

---

## 7. Design Decisions

| Decision | Choice | Rationale |
|----------|--------|-----------|
| Color scheme | Navy/slate blue | Trustworthy, professional |
| Typography | Lora + Source Sans 3 | Distinctive yet readable |
| Dark mode | CSS variables + localStorage | No flash on load, persists |
| Animations | CSS @keyframes | No JS library needed |
| Font weight | 400 minimum | WCAG readability |

---

## 8. Constraints

- **Budget:** $0 recurring (domain $10 yr 1, $17 yr 2+)
- **Time:** Build in days not weeks — MVP first
- **Skills:** PM owner learning to code — AI-assisted development
- **Tools:** Free tier only across all services

---

## 9. Dependencies

| Dependency | Risk | Mitigation |
|------------|------|------------|
| GitHub Pages uptime | Low — 99.9% SLA | Backup at tanyaturitto.github.io |
| Google Fonts CDN | Low | Fonts degrade to system fonts |
| Porkbun domain renewal | Medium — annual cost | Calendar reminder set |
| Cloudflare email routing | Low — free tier stable | Gmail always accessible directly |

---

## 10. Timeline

| Milestone | Date | Status |
|-----------|------|--------|
| Site designed and built | March 2026 | ✅ Done |
| WCAG audit and fixes | March 2026 | ✅ Done |
| GitHub repo created | March 2026 | ✅ Done |
| Custom domain connected | March 2026 | ✅ Done |
| Professional email set up | March 2026 | 🔄 In Progress |
| Documentation complete | March 2026 | 🔄 In Progress |
| HTTPS enforced | March 2026 | 🔄 In Progress |
| Lighthouse audit | TBD | 📋 Backlog |

---

## 11. Future Considerations (v2+)

- Add Google Analytics to measure visitor engagement
- Add Open Graph meta tags for rich LinkedIn previews
- Add Formspree contact form — no backend needed
- Add /projects page as portfolio grows
- Run Lighthouse audit targeting 100 across all categories
- Add case study writeup for this project

---

*This PRD is part of the Wise Builder AI PM Portfolio  
by Tanya Turitto · wisebuilder.me · Tanya@wisebuilder.me*
