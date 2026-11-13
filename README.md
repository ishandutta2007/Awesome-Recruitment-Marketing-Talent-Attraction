# Awesome-Recruitment-Marketing-Talent-Attraction

# Awesome Recruitment Marketing & Talent Attraction

> A curated list of top Recruitment Marketing and Talent Attraction platforms — both SaaS/Hosted commercial solutions and open-source alternatives for building employer brand, nurturing talent pipelines, and engaging candidates.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Phenom People](#phenom-people)
  - [Beamery](#beamery)
  - [SmashFly](#smashfly)
  - [Yello](#yello)
  - [Radancy](#radancy)
  - [Symphony Talent](#symphony-talent)
  - [SmartRecruiters](#smartrecruiters)
  - [Jobvite](#jobvite)
- [Open-Source Software](#-open-source-software)
  - [Sudohired](#sudohired)
  - [Euron Open Talent Network](#euron-open-talent-network)
  - [OpenCATS](#opencats)
  - [Ever Gauzy](#ever-gauzy)
  - [Good Dev Hunting](#good-dev-hunting)
  - [Referrer Mailer](#referrer-mailer)
  - [OpenHR Founder AI](#openhr-founder-ai)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Recruitment Marketing and Talent Attraction platforms. These are not open-source but are included as reference points for feature comparison.

### Phenom People
**Type:** Talent experience management with AI-powered CRM  
Phenom is a comprehensive Talent Experience Management platform covering career sites, CRM, chat, and AI-powered candidate matching. It is positioned for enterprises wanting to personalize the candidate journey from first touch through hiring, with strong employer branding and programmatic job advertising capabilities.

### Beamery
**Type:** Talent operating system with CRM and engagement  
Beamery is a Talent Operating System that assists HR teams in attracting, engaging, and retaining talent through AI-powered recruitment marketing, CRM, and employee engagement solutions [citation:13]. It focuses on building talent pipelines and nurturing passive candidates over time, making it a strong choice for organizations with high-volume or specialized hiring needs.

### SmashFly
**Type:** Recruitment marketing platform with programmatic advertising  
SmashFly (now part of Symphony Talent) provides recruitment marketing automation, programmatic job advertising, and candidate relationship management. It is positioned for enterprises wanting to unify their recruitment marketing efforts across channels.

### Yello
**Type:** Talent acquisition with CRM and events  
Yello provides a talent acquisition platform with CRM capabilities, event management, and candidate engagement. It is particularly strong for campus recruiting and high-volume hiring events, with mobile-friendly candidate check-in and pipeline management.

### Radancy
**Type:** Employer brand and career site platform  
Radancy (formerly TMP Worldwide) specializes in employer branding and career site development, with programmatic media buying and talent attraction analytics. It is positioned for large enterprises wanting a comprehensive employer brand and digital recruitment marketing strategy.

### Symphony Talent
**Type:** Recruitment marketing and employer brand  
Symphony Talent (which acquired SmashFly) provides recruitment marketing, employer branding, and candidate experience solutions. It combines CRM, career site management, and programmatic advertising into a unified platform for enterprise talent attraction.

### SmartRecruiters
**Type:** Talent acquisition suite with marketing capabilities  
SmartRecruiters provides an enterprise talent acquisition platform with built-in CRM, career site builder, and recruitment marketing features. It is positioned as an all-in-one hiring platform rather than a standalone recruitment marketing tool, with a strong marketplace of integrations.

### Jobvite
**Type:** Talent acquisition with recruitment marketing  
Jobvite provides an end-to-end talent acquisition suite including recruitment marketing, CRM, and applicant tracking. It is positioned for mid-market to enterprise organizations wanting a unified hiring platform with marketing automation built in.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Recruitment Marketing and Talent Attraction tools. The open-source ecosystem is **fragmented**—most projects are early-stage, narrowly scoped, or embedded within broader HR/ATS platforms rather than direct Phenom or Beamery equivalents.

### Sudohired
**Stack:** Node.js / PostgreSQL / Docker | **License:** Open Source  
Sudohired is an **open-source, self-hosted autonomous AI recruiting agent** explicitly positioned as "no SaaS, no subscriptions, no success fees" [citation:1]. It sources, engages, vets, and books meetings with candidates autonomously, with a unified talent pool, Kanban pipeline, and agent activity log. Key features include AI-personalized email outreach (OpenAI + Resend), conversational voice calls (Gemini Live + Twilio), and autonomous interview booking (Google Calendar + Meet) [citation:1]. It is **not** a marketing CRM but an agentic outreach tool for talent engagement.  
**Best for:** Technical recruiting teams wanting a self-hosted AI agent to automate candidate sourcing, outreach, and scheduling without per-seat SaaS fees, accepting the operational overhead of API key management and Docker deployment.

### Euron Open Talent Network
**Stack:** TypeScript / PostgreSQL / Redis / Terraform (AWS) | **License:** Open Source  
Euron is an open-source **professional network like LinkedIn** with talent pages, verified recruiters, jobs with a live hiring pipeline, consent-based contact unlock, messaging, a feed, and an admin control plane [citation:4][citation:7]. For talent attraction, it provides **talent pages** with headline, about, experience, education, projects, skills with endorsements, certifications, links, and badges with evidence. Per-section audience controls (everyone, connections, verified recruiters) and **consent-based contact details** (recruiters must be verified, must ask, and see only channels the candidate chooses, with every view logged) make it a privacy-first alternative to LinkedIn for organizations running their own talent network [citation:7].  
**Best for:** Organizations wanting to run their own professional talent network with strong privacy controls and verified recruiter workflows, accepting the substantial AWS/Terraform infrastructure requirements.

### OpenCATS
**Stack:** PHP / MySQL | **License:** GPL-3.0  
OpenCATS is a free and open-source **Applicant Tracking System (ATS) and recruitment CRM** for staffing agencies and hiring teams, managing the process from job posting through candidate selection and submission . While it is an ATS rather than a recruitment marketing platform, it provides the candidate database and pipeline foundation that talent attraction feeds into. An active modernization roadmap covers PHP 8.4/8.5 fixes, database and UI improvements, and API/integration features .  
**Best for:** Staffing agencies wanting a proven open-source ATS foundation, accepting that talent attraction and marketing capabilities must be built or integrated separately.

### Ever Gauzy
**Stack:** TypeScript / NestJS / Angular / PostgreSQL | **License:** AGPL-3.0  
Ever Gauzy is an open-source business management platform (ERP/CRM/HRM) that includes an **Applicant Tracking System (ATS)** module covering candidates, interviews, and hiring workflows [citation:8]. It is part of a broader platform with CRM, HRM, project management, and time tracking. While not a dedicated recruitment marketing tool, its CRM and ATS modules can support talent pipeline management within a unified business platform.  
**Best for:** Organizations already using or considering Gauzy for business management wanting ATS and CRM capabilities in the same platform, accepting the broader ERP scope.

### Good Dev Hunting
**Stack:** Next.js / TypeScript / Prisma / PostgreSQL | **License:** GPL-3.0  
Good Dev Hunting is a free, open-source platform for connecting skilled software engineers with those needing tech talent [citation:11]. Features include advanced filtering (technology, seniority, availability, location, skill area), customizable developer profiles (1500-character bios), direct communication, and manual moderation for quality [citation:11]. It is a **talent marketplace** rather than a recruitment marketing suite, but it provides a niche channel for tech talent attraction.  
**Best for:** Tech-focused organizations wanting an open-source talent marketplace alternative for developer hiring, accepting a narrower scope than enterprise recruitment marketing platforms.

### Referrer Mailer
**Stack:** Go / MongoDB / Angular / Gemini | **License:** Open Source  
Referrer Mailer is a self-hosted referral system that automates resume analysis, candidate screening, and email notifications using Gemini 2.5 Flash [citation:10]. Features include AI-powered candidate screening and summaries, AI resume customization for job descriptions, personalized cold email drafting, and network/rolodex management with contact import from sent emails [citation:10]. It is an **outreach and referral tool** rather than a marketing CRM, but supports personalized candidate engagement.  
**Best for:** Individual recruiters and small teams wanting AI-assisted referral outreach and candidate screening, accepting the Go/MongoDB/Angular stack requirements.

### OpenHR Founder AI
**Stack:** React / Next.js / Node.js / Supabase / FastAPI | **License:** MIT  
OpenHR Founder AI is an open-source **HR and talent matching platform** focused on AI-powered co-founder and developer matching for startups [citation:2]. It includes profile enrichment pipelines, GitHub integration for skill extraction, and AI agent workflows for matching. While not a traditional recruitment marketing platform, it represents an open-source approach to talent discovery and matching for startup ecosystems.  
**Best for:** Startup ecosystems and technical founders wanting AI-assisted talent matching, accepting a narrow focus on co-founder/developer matching rather than broad recruitment marketing.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Recruitment Marketing Focus | Candidate CRM | Self-Hosted | Best For |
|----------|---------|-------|----------------------------|---------------|-------------|----------|
| **Phenom** | Proprietary | Cloud | ✅ Talent experience | ✅ | ❌ | Enterprise talent experience |
| **Beamery** | Proprietary | Cloud | ✅ Talent CRM | ✅ | ❌ | Pipeline nurturing |
| **SmashFly** | Proprietary | Cloud | ✅ Programmatic ads | ✅ | ❌ | Recruitment marketing automation |
| **Yello** | Proprietary | Cloud | (Events) | ✅ | ❌ | Campus/event recruiting |
| **Sudohired** | Open Source | Node.js/Postgres | (Agentic outreach) | ✅ Talent pool | ✅ | AI sourcing + outreach |
| **Euron Network** | Open Source | TypeScript/AWS | (Talent network) | ✅ Consent-based | ✅ | Privacy-first talent network |
| **OpenCATS** | GPL-3.0 | PHP/MySQL | ❌ (ATS) | ✅ | ✅ | ATS foundation |
| **Ever Gauzy** | AGPL-3.0 | TypeScript/NestJS | (CRM/ATS) | ✅ | ✅ | Unified business + ATS |
| **Good Dev Hunting** | GPL-3.0 | Next.js/Postgres | (Marketplace) | (Filtering) | ✅ | Tech talent marketplace |
| **Referrer Mailer** | Open Source | Go/MongoDB | (Referral outreach) | (Rolodex) | ✅ | AI referral outreach |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Recruitment Marketing or Talent Attraction tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem for **dedicated recruitment marketing** is **very limited and fragmented**. **Sudohired** is the most purpose-built open-source effort for talent attraction, providing an autonomous AI agent that sources, engages, and books meetings without SaaS fees [citation:1]. **Euron Open Talent Network** offers a uniquely privacy-first approach to running your own professional talent network with consent-based contact [citation:7]. **OpenCATS** remains the mature open-source ATS foundation , while **Ever Gauzy** bundles ATS within a broader business platform [citation:8]. No open-source project replicates the full employer branding, programmatic advertising, and talent CRM breadth of Phenom or Beamery.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
