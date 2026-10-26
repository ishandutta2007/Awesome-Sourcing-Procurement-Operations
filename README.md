# Awesome-Sourcing-Procurement-Operations

# Top Sourcing & Procurement Operations Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Source-to-Pay Automation, Strategic Sourcing & Procurement Orchestration*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Sourcing & Procurement Operations**. These tools enable organizations to automate the source-to-pay lifecycle—from intake and sourcing events through contract execution, purchase orders, invoicing, and supplier collaboration—while enforcing compliance and controlling spend.

**Examples** include ServiceNow Sourcing and Procurement Operations, Coupa, SAP Ariba, Ivalua, Jaggaer, Zip, GEP SMART, Scout RFP (Workday Strategic Sourcing), Fairmarkit, and Keelvar (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted procurement orchestration, RFQ automation, and AI-assisted sourcing intelligence—ideal for procurement teams, developers, and organizations building sovereign source-to-pay infrastructure without per-transaction or per-seat licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Sourcing and Procurement Operations](https://www.servicenow.com/)**  
  Procurement service management solution on the Now Platform with ShoppingHub guided buying, virtual agent deflection, centralized procurement workspace, configurable playbooks, and real-time SLA analytics; integrates with existing ERP and procurement systems to automate source-to-receipt workflows .

- **[Coupa](https://www.coupa.com/)**  
  Agentic AI-native spend management platform with Coupa Navi Agent Studio for building procurement-specific AI agents; recent releases add BOM-driven sourcing for direct materials, category strategy integration to execute events against approved plans, and Coupa Orchestrator for drag-and-drop custom workflows across sourcing, contracting, and supplier management .

- **[SAP Ariba](https://www.sap.com/)**  
  Comprehensive source-to-pay suite with category management (PESTLE external factors analysis), supplier lifecycle and performance, spend control tower with industry benchmarks, and AI copilot Joule for supplier data navigation and approval workflows .

- **[Ivalua](https://www.ivalua.com/)**  
  Source-to-Contract solution with AI-powered Intake Management that captures demand from any channel and routes it into correct S2C workflows; includes intelligent agents for supplier questionnaire analysis, contract knowledge interaction, and conversational analytics via IVA assistant .

- **[Jaggaer](https://www.jaggaer.com/)**  
  Spend management suite with 25.3 release introducing bulk RFx template import to launch hundreds of events from one file, conditional assessment rules, automated supplier gating to block unqualified suppliers, and Intake & Orchestration for a guided "one front door" request experience .

- **[Zip](https://zip.com/)**  
  Intake-to-procure platform with AI-powered workflow routing from natural language, AI-assisted intake that pre-fills requests from documents, Price Negotiation Agent projecting 3-5% savings per contract, Invoice-to-Contract Compliance Agent, and PO Management add-on for full purchase order visibility .

- **[GEP SMART](https://www.gep.com/)**  
  AI-powered source-to-pay software covering spend visibility, RFx and e-auction management with auto-scoring, contract lifecycle management with AI-based risk assessment, supplier performance dashboards, and guided buying through to autonomous procurement .

- **[Scout RFP (Workday Strategic Sourcing)](https://www.workday.com/)**  
  Strategic sourcing platform with API-driven event management, bid line items, award management, contract lifecycle, and supplier contact management; integrated into Workday's broader spend management ecosystem .

- **[Fairmarkit](https://www.fairmarkit.com/)**  
  Automated sourcing platform for tail spend and below-threshold purchases; buyers create events, receive AI-recommended supplier suggestions, and compare responses side-by-side; integrates directly with ERP and P2P platforms .

- **[Keelvar](https://www.keelvar.com/)**  
  AI-driven sourcing optimization platform with powerful scenario optimization engine for "what-if" analyses, automation bots for recurring purchase events, and simultaneous evaluation of multiple supplier constraints and risk variables for complex large-scale sourcing .

## Open-Source GitHub Projects

- **[mcp-procurement](https://github.com/zavora-ai/mcp-procurement)**  
  AI-powered procurement engine with 37 MCP tools covering the full source-to-pay lifecycle: supplier management, RFQ creation and comparison, purchase orders with approval gates, contracts, goods receipt, three-way matching, budgets, and diversity tracking; includes 10 intelligence tools for supplier risk scoring, price benchmarking, carbon footprint, demand forecasting, savings opportunity detection, maverick spend detection, and negotiation briefs .

- **[VendSync (BidFlow)](https://github.com/RavalMunjal/VendSync)**  
  Full-stack procurement and vendor management ERP covering RFQ creation through invoice generation; features role-based access (Admin, Manager, Procurement Officer, Vendor), vendor portal for independent quotation submission, side-by-side quotation comparison with lowest-price highlighting, structured approval workflows, auto-generated purchase orders and invoices with PDF export, and real-time analytics dashboards; built with React/Node.js/MongoDB .

- **[e-procure](https://github.com/Gichure/e-procure)**  
  Spring Boot microservices-based e-procurement system with modules for purchase requisition, purchase orders, vendor management, bid management, invoice management, payment processing, and BPMN workflow via Camunda; includes Apache Kafka messaging, Keycloak authentication, and Docker/Kubernetes deployment support; MIT licensed .

- **[Prozorro](https://github.com/openprocurement)**  
  Open-source public e-procurement system (Apache 2.0) developed for Ukraine with Open Contracting Data Standard compliance; supports competitive tenders, auction mechanisms, and multi-platform API integration; has demonstrated $6 billion in public fund savings and expanded to defense procurement and asset sales .

- **[OpenTradeIntel](https://pypi.org/project/opentradeintel/)**  
  Open-source procurement and B2B sourcing intelligence engine that queries EU public procurement notices from the TED Search API, normalizes them into typed tenders, and ranks them against local supplier catalogs with deterministic 0–100 matching scores; includes CLI, FastAPI, and MCP adapter; fully local and offline-capable for core features .

- **[aribaiq](https://pypi.org/project/aribaiq/)**  
  Open-source Python library for AI-powered procurement analytics with supplier intelligence scoring (on-time rate, defect rate, ESG score, spend concentration), spend visibility and optimization signals, ESG-weighted evaluation, responsible AI checks (missingness, invalid values, representation imbalance), and GenAI-ready prompt generation for copilots and LLM workflows; MIT licensed .

### Additional Strong Open-Source Options

- **GitHub `procurement-system` topic** — 37+ public repositories covering AI-powered procurement intelligence agents, multi-agent procurement collaboration platforms, electronic bidding systems, and transparent tendering foundations for public-sector workflows .
- **AI-powered procurement intelligence agents** — Community projects with local LLM integration, document OCR, vendor scoring, and web research for analyzing bids and extracting structured data privately .
- **Transparent tendering platforms** — Open-source foundations for supplier trust, bid evaluation, contract awards, and auditable public-sector procurement workflows .

**Frameworks for building custom systems**: Combine **mcp-procurement** for AI-assisted source-to-pay orchestration with intelligence tooling, **VendSync** for full RFQ-to-invoice workflow with vendor portal, **e-procure** for microservices-based enterprise procurement with BPMN workflows, and **OpenTradeIntel** for tender discovery and catalog matching in a self-hosted sourcing and procurement operations stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Procurement platforms handling supplier and financial data must comply with applicable regulations (anti-corruption laws, public procurement rules, data privacy requirements).
- Self-hosted open-source solutions require proper security hardening, ERP/finance integration planning, and workflow customization for approval gates and compliance controls.
- Verify license terms for commercial use; mcp-procurement is an open-source MCP server, VendSync and e-procure use MIT, Prozorro uses Apache 2.0, and OpenTradeIntel/aribaiq use permissive licenses.

---

**Made for procurement teams, sourcing managers, supply chain analysts, and P2P automation engineers.**  
Let's make sourcing and procurement operations more open, intelligent, and efficient.
