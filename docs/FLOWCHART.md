# User Journey Flowcharts
**Project:** Wise Builder Resume Portfolio Site  
**Author:** Tanya Turitto  
**Last Updated:** March 2026  

---

## 1. Visitor Journey — First Time User
```mermaid
flowchart TD
    A([Visitor lands on wisebuilder.me]) --> B{How did they arrive?}
    B -->|LinkedIn link| C[Hero section loads]
    B -->|Google search| C
    B -->|Direct URL| C
    C --> D[Reads name, title, tagline]
    D --> E{Interested?}
    E -->|No| F([Leaves site])
    E -->|Yes| G[Scrolls to About]
    G --> H[Reviews skills and stats]
    H --> I[Reads Experience timeline]
    I --> J[Checks Certifications]
    J --> K{Ready to connect?}
    K -->|Not yet| L[Bookmarks site]
    K -->|Yes| M[Clicks LinkedIn or Email]
    M --> N([Makes contact])
```

---

## 2. Hiring Manager Journey
```mermaid
flowchart LR
    A([Receives LinkedIn application]) --> B[Clicks portfolio link]
    B --> C[Lands on wisebuilder.me]
    C --> D[Scans hero section]
    D --> E[Clicks GitHub link]
    E --> F[Views repo README]
    F --> G[Checks Project Board]
    G --> H[Reviews docs/ folder]
    H --> I[Reads PRD]
    I --> J{Impressed?}
    J -->|Yes| K[Schedules interview]
    J -->|Needs more| L[Reviews Experience section]
    L --> K
```

---

## 3. Site Build & Deploy Flow
```mermaid
flowchart TD
    A([Edit index.html in VS Code]) --> B[Save file]
    B --> C[Live Server previews change locally]
    C --> D{Happy with change?}
    D -->|No| A
    D -->|Yes| E[git add .]
    E --> F[git commit -m message]
    F --> G[git push]
    G --> H[GitHub receives push]
    H --> I[GitHub Pages builds site]
    I --> J([wisebuilder.me updates live\nin ~30 seconds])
```

---

## 4. Domain & Email Routing Flow
```mermaid
flowchart LR
    A([Visitor types wisebuilder.me]) --> B[Porkbun DNS lookup]
    B --> C[Routes to GitHub Pages servers]
    C --> D([Site loads in browser])

    E([Email sent to Tanya@wisebuilder.me]) --> F[Cloudflare Email Routing]
    F --> G([Delivered to tnturitto@gmail.com])
```

---

## 5. Future Platform Architecture
```mermaid
flowchart TD
    A([wisebuilder.me]) --> B[/ — Resume Portfolio]
    A --> C[/gift-helper — Project 2]
    A --> D[/project-3 — TBD]
    A --> E[/project-4 — TBD]
    
    B --> F[docs/PRD.md]
    B --> G[docs/FLOWCHART.md]
    B --> H[docs/INFRA-TOOLING.md]
    B --> I[docs/RETROSPECTIVE.md]
    
    C --> J[docs/PRD.md]
    C --> K[docs/FLOWCHART.md]
```

---

*This document is part of the Wise Builder AI PM Portfolio  
by Tanya Turitto · wisebuilder.me · Tanya@wisebuilder.me*
