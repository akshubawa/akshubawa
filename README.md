<div align="center">

# AKSHAY NEGI

### Software Engineer

**Mobile · Backend · AI · Product Engineering**

> I build software that has to work in the real world.

<br>

<a href="https://linkedin.com/in/akshay-negi-86b617252">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:akshaynegi0264@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://x.com/akshay_exe">
  <img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" />
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=akshubawa&style=flat-square&label=PROFILE+VIEWS" />

</div>

---

## `whoami`

I'm a Software Engineer interested in the part of software development **after the tutorial ends**.

I enjoy taking a problem all the way through:

```text
Problem
   ↓
Requirements
   ↓
Architecture
   ↓
Implementation
   ↓
Deployment
   ↓
Production
   ↓
Iteration
```

My experience spans **mobile applications, backend systems, SaaS products, offline-first architecture, real-time synchronization, and AI-powered applications**.

Currently, I work at **Prosessed.ai**, building production software across the OrderIT ecosystem and AI-powered product experiences.

Outside of work, I build products independently, including **Organised Gym**, a gym management SaaS platform.

---

## Impact

<div align="center">

| 250K+ | 2B+ | 50+ | 15+ |
|:---:|:---:|:---:|:---:|
| API requests / day | AI-analyzed clicks / month | Global businesses | Gyms |

| 10K+ | 1,000+ | 130K+ | 2× |
|:---:|:---:|:---:|:---:|
| App downloads | Gym members | API requests / month | Hackathon Winner |

</div>

---

# What I've Built

> Not everything I've worked on is public.
>
> Some of my most meaningful engineering work has been inside production systems, so this section focuses on **what I built and the engineering problems behind it**, rather than pretending everything belongs in a public repository.

---

## 01 · OrderIT

**B2B commerce · Mobile · Offline-first systems**  
**Prosessed.ai**

OrderIT is a B2B ordering platform built for the wholesale food industry.

My work here has involved building production mobile functionality and solving problems that appear when software has to operate reliably in real business environments.

### The interesting problem

**What happens when the user has no internet?**

Instead of assuming a permanently connected device, I worked on an **offline-first order management architecture** that allows users to continue working locally and synchronize data when connectivity returns.

### Architecture

```text
Flutter
  │
  ├── Local persistence
  │     ├── SQLite
  │     └── Shared Preferences
  │
  ├── Application state
  │
  ├── Backend synchronization
  │
  └── Production APIs
```

### Highlights

- Built offline-first order management functionality
- Implemented local persistence using SQLite and Shared Preferences
- Supported automatic synchronization when connectivity returns
- Worked on a hybrid local + backend data flow
- Supported **500+ daily order updates**
- Worked across requirements, development, deployment and maintenance
- Contributed to production systems handling **250K+ API requests/day**

---

## 02 · OrderIT Internal

**Internal operations · Fulfillment · Logistics**  
**Prosessed.ai**

> **OrderIT Internal is a separate application from OrderIT.**

It is an internal operations platform designed to streamline:

- Warehouse picking
- Delivery execution
- Employee attendance
- Operational analytics
- Fulfillment workflows

The application acts as an operational backbone for **fulfillment teams, drivers and managers**.

### Engineering focus

```text
Operational workflows
        +
Mobile application
        +
Backend services
        +
Real-time operational visibility
        +
Accountability
```

I developed **OrderIT Internal from the ground up**, contributing to the application used to support operations across **50+ global food wholesalers and manufacturers**.

The interesting part wasn't simply building screens.

It was translating operational requirements into software that teams could actually use as part of their daily workflow.

---

## 03 · Jerry AI

**AI-powered product experience**  
**Prosessed.ai**

Jerry AI is an **LLM-powered chatbot** integrated into the product ecosystem.

I worked on the frontend experience and AI workflow integration.

### Stack

`Flutter` · `LangGraph` · `LangChain` · `Gemini`

### Workflow

```text
User
 │
 ▼
Flutter Application
 │
 ▼
AI Workflow
 │
 ├── LangGraph
 ├── LangChain
 └── Gemini
 │
 ▼
Response
```

The work combines traditional application engineering with **LLM-powered workflows**.

---

## 04 · TrackOG

**AI-powered performance marketing**  
**Digital Work India**

> **TrackOG is a completely separate product from OrderIT.**

I contributed reusable Flutter modules to the platform.

TrackOG operates at significant scale, processing **2B+ AI-analyzed clicks per month**.

### What I worked on

- Reusable Flutter modules
- Mobile application development
- Product-scale frontend engineering
- Integration with large backend systems

---

## 05 · Organised Gym

**SaaS · Product Engineering · Backend**  
**Independent Product**

Organised Gym is a gym management SaaS platform I designed and built around real operational requirements.

This is one of the projects where I have worked across almost the entire product lifecycle.

### From idea to production

```text
Product Requirements
        ↓
System Design
        ↓
Database Design
        ↓
Backend APIs
        ↓
Flutter Application
        ↓
Authentication
        ↓
Deployment
        ↓
Production
```

### Stack

`Flutter` · `FastAPI` · `PostgreSQL` · `AWS`

### What I built

- Backend architecture
- Database schema
- REST APIs
- JWT authentication
- Flutter application
- BLoC-based application architecture
- AWS deployment
- Railway deployment

### Current scale

| Metric | Scale |
|---|---:|
| Gyms | **15+** |
| Members | **1,000+** |
| API requests | **130K+ / month** |

> The goal wasn't to build another demo CRUD application.
>
> It was to build something that gyms could actually use to run their operations.

---

## 06 · Pruddy

**Gamified self-care · iOS**

`Flutter` · `Firebase` · `Clean Architecture`

Built and launched a gamified self-care iOS application with a coin-based rewards system designed to encourage engagement.

### Engineering focus

- Flutter application development
- Firebase integration
- Clean Architecture
- UI rendering
- Animation performance

**Result:** improved animation performance and reduced animation jank by **40%**.

---

## 07 · RakshakCode

**Emergency communication · Mobile**

`Flutter` · `QR` · `Video Calling`

Built RakshakCode from scratch around emergency communication and vehicle identification.

### Features

- QR-based emergency video calling
- Instant vehicle identification
- Reusable Flutter modules

**Result:** **10K+ app downloads**

---

# Engineering

> I don't believe architecture should exist just to make a project look sophisticated.
>
> I care about architecture when **it solves an actual problem**.

### Offline-first systems

Designing applications that remain useful when connectivity is unreliable.

### State & synchronization

Thinking about where data lives, which state is authoritative, and how local and backend state converge.

### Application architecture

Using patterns such as **BLoC, Clean Architecture and MVVM** when they make software easier to maintain and evolve.

### Backend systems

Designing APIs and data models around real product requirements, not isolated endpoints.

### Product engineering

Understanding the feature beyond the ticket:

```text
Why does this exist?
       ↓
Who uses it?
       ↓
What can go wrong?
       ↓
How should it behave?
       ↓
How do we know it works?
       ↓
How does it behave in production?
```

---

# Stack

<div align="center">

| Area | Technologies |
|:---|:---|
| **Languages** | Dart · Python · Java · C++ · JavaScript |
| **Mobile** | Flutter · Android · iOS |
| **Backend** | FastAPI · Flask · REST APIs · JWT |
| **Architecture** | BLoC · Clean Architecture · MVVM · High-Level Design |
| **Databases** | PostgreSQL · SQLite · Hive |
| **Cloud** | AWS · Firebase · Railway · Supabase · Azure |
| **AI** | LangChain · LangGraph · Gemini |
| **Tools** | Git · GitHub · Postman · Jira · Figma · Notion |

</div>

---

# Timeline

```text
2024
│
├── Digital Work India
│   │
│   ├── RakshakCode
│   │   └── Emergency communication · 10K+ downloads
│   │
│   └── TrackOG
│       └── AI-powered performance marketing · 2B+ AI-analyzed clicks / month
│
│
2025
│
├── Prosessed.ai
│   └── Software Engineer Intern
│       ├── Flutter
│       ├── BLoC
│       ├── Clean Architecture
│       ├── Hybrid local + backend synchronization
│       └── 30+ application screens
│
│
2026
│
└── Prosessed.ai
    └── Software Engineer · Mobile
        │
        ├── OrderIT
        │   ├── Offline-first architecture
        │   ├── Local persistence
        │   ├── Synchronization
        │   └── Production APIs
        │
        ├── OrderIT Internal
        │   └── Internal operations platform
        │
        └── Jerry AI
            ├── LangGraph
            ├── LangChain
            └── Gemini
```

---

# What I Enjoy

```text
                    BUILDING
                       │
           ┌───────────┼───────────┐
           │           │           │
        MOBILE      BACKEND        AI
           │           │           │
           └───────────┼───────────┘
                       │
                      SAAS
                       │
                       ▼
                 REAL PROBLEMS
                       │
                       ▼
                  REAL USERS
                       │
                       ▼
                   PRODUCTION
```

I particularly enjoy problems where the answer isn't just:

> **"Build another screen."**

but instead:

> **"How should this system actually work?"**

---

# GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=akshubawa&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" height="165" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=akshubawa&layout=compact&hide_border=true&langs_count=8" height="165" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=akshubawa&hide_border=true" />

</div>

---

# Beyond Code

## 2× Hackathon Winner

I enjoy hackathons because they compress the entire product-building process into a few hours or days.

You start with:

**A problem**

and end with:

**Something people can actually interact with.**

The constraint is part of the fun.

---

# Currently

### Software Engineer @ Prosessed.ai

Working across:

`Flutter` · `Production Systems` · `Backend APIs` · `AI`

Currently interested in going deeper into:

- System design
- Scalable application architecture
- AI-powered products
- Distributed and offline-first systems
- Building products end-to-end

---

# Let's Connect

I'm always interested in interesting products, difficult engineering problems, and people who enjoy building things.

If you're working on something around **mobile, backend, AI or SaaS**, feel free to reach out.

<div align="center">

<a href="https://linkedin.com/in/akshay-negi-86b617252">LinkedIn</a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="https://x.com/akshay_exe">X</a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="mailto:akshaynegi0264@gmail.com">Email</a>

<br><br>

### Build things. Ship them. Learn from production.

</div>
