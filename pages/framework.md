---
layout: default
title: "The Framework"
---

# The Framework

The workshop produced a co-designed framework for coordinating national biomedical data science resources — spanning infrastructure, training, and people — structured around five interdependent pillars. This framework was agreed in principle by all participants and provides the foundation for a phased implementation roadmap. It reflects the community's conviction that infrastructure alone is insufficient: without coordinated training, sustainable career pathways, and shared expertise, even the best-resourced platforms will fail to deliver their potential.

<div class="box box-blue">
<strong>How this framework was built</strong>
It emerged from structured discussions involving researchers, infrastructure providers, training specialists, funders, and institutional leaders — all responding to evidence gathered over the preceding year across infrastructure provision, training availability, workforce capacity, and institutional costs. It reflects what the community identified as essential rather than any single organisation's needs.
</div>

---

## The five pillars

The framework rests on five pillars, each addressing a distinct dimension of the coordination challenge. Three pillars address the enabling conditions (infrastructure, governance, authentication and access), while two address the often-overlooked human dimensions (data ownership and IP, careers and training). Importantly, participants recognised that these pillars are highly interconnected — progress on one often depends on progress on others — and that the people-focused pillars are not secondary to the technical ones.

<div class="diagram-container" markdown="0">
<svg viewBox="0 0 800 520" xmlns="http://www.w3.org/2000/svg" style="max-width:750px">
  <!-- Base platform -->
  <rect x="50" y="400" width="700" height="60" rx="8" fill="#1a2744"/>
  <text x="400" y="437" text-anchor="middle" fill="white" font-family="Inter,sans-serif" font-size="16" font-weight="600">Shared National Biomedical Data Science Model</text>

  <!-- Pillars -->
  <rect x="70" y="120" width="120" height="270" rx="6" fill="#2563eb" opacity="0.9"/>
  <text x="130" y="260" text-anchor="middle" fill="white" font-family="Inter,sans-serif" font-size="13" font-weight="600" transform="rotate(-90 130 260)">Infrastructure</text>

  <rect x="210" y="120" width="120" height="270" rx="6" fill="#0d9488" opacity="0.9"/>
  <text x="270" y="260" text-anchor="middle" fill="white" font-family="Inter,sans-serif" font-size="13" font-weight="600" transform="rotate(-90 270 260)">Governance</text>

  <rect x="350" y="120" width="120" height="270" rx="6" fill="#7c3aed" opacity="0.9"/>
  <text x="410" y="260" text-anchor="middle" fill="white" font-family="Inter,sans-serif" font-size="13" font-weight="600" transform="rotate(-90 410 260)">Authentication &amp; Access</text>

  <rect x="490" y="120" width="120" height="270" rx="6" fill="#e11d48" opacity="0.9"/>
  <text x="550" y="260" text-anchor="middle" fill="white" font-family="Inter,sans-serif" font-size="13" font-weight="600" transform="rotate(-90 550 260)">Data Ownership &amp; IP</text>

  <rect x="630" y="120" width="120" height="270" rx="6" fill="#f59e0b" opacity="0.9"/>
  <text x="690" y="260" text-anchor="middle" fill="white" font-family="Inter,sans-serif" font-size="13" font-weight="600" transform="rotate(-90 690 260)">Careers &amp; Training</text>

  <!-- Roof / outcome -->
  <polygon points="50,110 400,30 750,110" fill="#1a2744" opacity="0.1"/>
  <polygon points="55,110 400,35 745,110" fill="none" stroke="#1a2744" stroke-width="2"/>
  <text x="400" y="82" text-anchor="middle" fill="#1a2744" font-family="Inter,sans-serif" font-size="14" font-weight="600">Coordinated, Sustainable, Equitable Access</text>

  <!-- Cross-cutting arrows -->
  <line x1="130" y1="105" x2="690" y2="105" stroke="#94a3b8" stroke-width="1" stroke-dasharray="6,4"/>
  <text x="400" y="100" text-anchor="middle" fill="#64748b" font-family="Inter,sans-serif" font-size="10" font-style="italic">Cross-cutting: People + Integration + Sustainability</text>
</svg>
</div>

---

## Pillar 1: Infrastructure

<div class="pillar">

### What this covers

The physical and digital infrastructure required for biomedical data science: compute (including HPC and cloud), storage, software platforms, and the skilled people who operate them.

### What already exists

Most nations already have significant infrastructure assets — HPC centres, cloud partnerships, domain-specific platforms, and emerging national data initiatives. The problem is the current fragmentation: resources exist but are disconnected, duplicated, or inaccessible to researchers who need them.

### Key findings from the workshop

- **Storage and compute** were identified as essential phase-1 requirements alongside file synchronisation and sharing capabilities
- **Cloud access** through national HPC providers was seen as an anchor for the model
- **Existing platforms** (national data repositories, domain-specific tools) should be connected, not replaced
- A **skills shortage** in research software engineering and data engineering was identified as a barrier as significant as any hardware gap

### What can be delivered in 12-18 months

- Exemplar projects demonstrating cross-institutional workflows
- A landscaping exercise documenting what exists and where gaps lie
- Community webinars to build awareness and connection

### What still needs scoping

- Full inventory of institutional infrastructure across participating organisations
- Costing models for shared services vs. duplicated institutional provision
- Gap analysis against international comparators
- Solid worked examples showing end-to-end workflows

</div>

---

## Pillar 2: Governance and decision rights

<div class="pillar" style="border-top-color: #0d9488">

### What this covers

How decisions are made about data access, infrastructure use, resource allocation, and strategic direction. This includes governance of the shared model itself and the governance frameworks applied to data within it.

### Key principle identified

> Governance should be based on principles rather than project-based funding. The question is how to evaluate risk under this approach.

### Key findings from the workshop

- Some **examples of good governance practice** already exist and should be extended rather than reinvented
- A **modular approach** was suggested — described as "3-in-1 Lego sets for governance" — flexible enough to accommodate different data types and use cases
- University responsibility over data generated, combined with a collaborative approach to access
- Data curation recognised as a form of "currency" within the system

### What can be delivered in 12-18 months

- Landscape and discovery exercise mapping existing governance models
- Identification of pathways and access model combinations
- Clarity on the funder-university relationship in data governance

### Risks of inaction

- National research capability falls behind international comparators
- Health inequalities widen without data-driven insights
- Research expertise leaves for better-resourced environments
- Further divergence between health and biomedical data ecosystems
- Universities continue to duplicate governance overhead individually, adding cost without improving outcomes

</div>

---

## Pillar 3: Authentication and access

<div class="pillar" style="border-top-color: #7c3aed">

### What this covers

How researchers, collaborators, and industry partners are identified, verified, and granted appropriate access to shared infrastructure and data. This includes the concept of a "research passport" — a portable identity that works across institutional boundaries.

### What already exists

- Institutional single sign-on systems and federated identity (e.g. eduroam-style)
- National researcher identifiers (e.g. ORCID)
- Government identity systems
- Existing safe-haven and trusted research environment access processes

### Key findings from the workshop

- A **research passport** concept emerged — a portable credential not tied to a single host institution
- An existing national **safe researcher registry** was cited as a model to build on
- Industry access must be designed in from the start, not bolted on later
- Current authentication systems are fragmented: what works at one institution may not be recognised at another

### Concrete next steps identified

1. Develop a working group specifically for authentication
2. Compile a list of common requirements for a minimum viable product
3. Formalise and document requirements for a biomedical research identifier
4. Identify exemplars of what is and is not working well currently
5. Engage with data controllers, institutions, industry, and government
6. Engage with national data bodies to promote shared requirements

### Risk of inaction

Too many disconnected systems create liability for bad actors and barriers for legitimate researchers.

</div>

---

## Pillar 4: Data ownership and intellectual property

<div class="pillar" style="border-top-color: #e11d48">

### What this covers

Who owns research data, how IP is managed in collaborative and shared environments, and how the rights and interests of data subjects (ultimately, citizens) are protected and respected.

### What already exists

- Domain expertise embedded in research groups
- Research data management teams working with contracts offices
- Shared service legal models at sector level
- Creative Commons and similar licensing frameworks
- PhD-level data agreements and institutional IP policies

### Key findings from the workshop

- **Agreement from all participating institutions to start conversations** around a shared services model for legal and IP support was identified as a deliverable within 12-18 months
- A **common resource pool for IP** (including IP training for academics and professional services staff) was proposed
- Industry terms need further exploration — they should be treated equitably but may require different models
- A pragmatic "80/20 rule" was explicitly endorsed: the framework may never fit every scenario, and that is acceptable

### A powerful framing that emerged

> How do we ensure there is a return to the "real" data owners — that is, the nation's citizens?

This question reframes data infrastructure as a public good and has potential as a narrative for public engagement and government advocacy.

### What still needs scoping

- Understanding of what legal agreements and frameworks currently exist across institutions
- Industry requirements and acceptable terms for data access and IP sharing
- Non-cost models that allow mutual benefit between academia and industry

</div>

---

## Pillar 5: Careers and training

<div class="pillar" style="border-top-color: #f59e0b">

### What this covers

Career pathways, professional development, training provision, and recognition for the people who make data science infrastructure work: data scientists, research software engineers, data stewards, bioinformaticians, and technical professionals. The survey evidence was stark: 76% of respondents working with mission-critical biomedical data had no formal training in data science, and existing training resources — where they existed — were fragmented across institutions and invisible to those who needed them most.

### Key findings from the workshop

The lack of career recognition and sustainable pathways for data professionals was identified as both a barrier to infrastructure development and a failure risk for the entire initiative.

- **Consistent signposting** to existing reputable training resources (e.g. Software Carpentry, Data Carpentry) was seen as a quick win
- A **scoping exercise** on current career development frameworks and accreditation schemes was identified as a priority
- **Cross-disciplinary mentoring schemes** were proposed to connect data scientists with domain researchers
- The **Technician Commitment** was cited as a recognition model to learn from

### What can be delivered in 12-18 months

- Community network events connecting PhDs, data scientists, and non-data-science mentors
- An inventory of what training and career development currently exists
- Scoping of accreditation frameworks and their applicability

### What still needs evidence

- Comprehensive mapping of available training and career pathways
- Assessment of the skills shortage (data science, data engineering, AI/ML, ethics, IT security)
- Understanding of what career development opportunities are actually taken up vs. merely offered

</div>

---

## Cross-cutting themes

Three themes emerged that cut across all five pillars:

<div class="grid-2">
<div class="box box-blue">
<strong>People before platforms</strong>
Career pathways, skills shortages, training fragmentation, and the need for dedicated coordination capacity were common discussion points. Three-quarters of biomedical researchers work with data they consider mission-critical but lack formal training in the methods they use daily. Any implementation plan that leads with technology and buries the people and training dimensions will fail to deliver the workforce needed to make shared infrastructure effective.
</div>

<div class="box box-teal">
<strong>Integration, not re-invention</strong>
Good training resources already exist but are fragmented and hard to find; infrastructure assets are significant but poorly coordinated. The framework should be "designed to be connected" — linking existing institutional investments, national data programmes, training provision, and international standards bodies into a coherent, discoverable whole.
</div>
</div>

<div class="box box-amber">
<strong>Sustainability from day one</strong>
Short-term or project-based funding was the single most cited failure risk. The framework must include a sustainability model — financial, institutional, and operational — from the outset. Baseline funding (not just pump-priming) was the clear preference.
</div>

---

## Implementation roadmap

The workshop produced a phased roadmap for taking the framework from agreement to action:

| Phase | Timeline | Key Activities |
|-------|----------|----------------|
| **Stakeholder mapping** | 1-3 months | Identify all relevant parties; convene a working group; agree terms of reference; produce a glossary of shared terms |
| **Landscape review** | 3-6 months | Audit existing infrastructure, governance, and training across institutions; identify gaps and duplication; develop a business case |
| **Analysis and pitch** | 6-12 months | SWOT/gap analysis; government and funder engagement; formal strategic case for investment |
| **Implementation** | 12+ months | Defined deliverables including shared resources, datasets, and IP frameworks; ongoing coordination via task-and-finish groups |

<div class="box box-rose">
<strong>A caution from the workshop</strong>
Participants explicitly warned about scope creep. A note on one flipchart read simply: "SCOPE CREEP" with arrows pointing to the need for focus. The 80/20 rule applies — the framework will never accommodate every scenario, and that is acceptable. The mechanism for maintaining focus must be designed into the governance of the working group.
</div>

---

**Next:** [The Toolkit](toolkit) — a practical, phase-by-phase guide for running similar initiatives
