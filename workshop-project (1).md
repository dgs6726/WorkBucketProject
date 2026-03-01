# Century Mold — Supply Chain Work Bucket Mapping Project

## Project Context

### What This Is
A workshop preparation project for Century Mold's COO-led organizational redesign initiative. The goal is to map the **current state** of supply chain work — who does what — so it can be compared against a proposed future-state org design during a facilitated workshop.

### Company Background
- **Century Mold**: ~$180M automotive manufacturing company (plastics injection molding)
- **6 production sites in North America**: Rochester, Shelbyville, Middletown, Pulaski, Queretaro (Mexico), Chihuahua (Mexico)
- **Serves Tier 1 automotive customers**, build-to-print
- Recently transitioned from geographic to category-based purchasing
- Evolving from centralized to center-led supply chain operations

### The Workshop
- **Sponsor**: Carlos Sanchez, COO
- **Objective**: Identify ideal organizational design, duplication of work, unnecessary coordination, and SG&A reduction opportunities
- **Approach**: Map current-state work buckets with owners → compare to Carlos' proposed future-state org → identify gaps, duplication, unclear ownership

### Carlos' Specific Ask
> Provide "work buckets with current owners" — what the work is, what happens in each bucket, who owns it. He wants to see duplication, confusion, shared ownership, and no ownership. Think about how to represent this visually and clearly.

---

## Key Design Decisions

- **Granularity**: Level 2 work streams (e.g., "Supplier Qualification"), not Level 1 domains or Level 3 tasks
- **Scope**: Supply Chain only, not full COO span — but flagging boundary work
- **Purchasing split**: By nature of work (strategic vs. tactical) rather than by spend category (direct vs. indirect)
- **Planning releases**: Classified as a planning function, not purchasing — lives under Planning & Inventory
- **Material Availability Management**: Removed as a standalone bucket — it's an outcome of effective planning, not a separate work system. Purchasing supports escalations as a secondary note.

---

## Flag Definitions

| Flag | Definition | Typical Signals | Workshop Question |
|------|-----------|-----------------|-------------------|
| **Boundary** | Bucket scope is poorly defined — activities bleed into adjacent buckets or absorb work that belongs elsewhere | Two teams both claim ownership; handoffs unclear; bucket name doesn't match actual content | "Where does this bucket start and stop, and does everyone agree?" |
| **Gap** | A necessary activity has no clear home — falls between buckets or is missing entirely | Work that "just happens" informally; recurring escalations because nobody owns a task | "Is there work that needs to be done that no bucket currently covers?" |
| **Duplication** | Same or nearly same activity performed in two or more buckets, creating redundant effort | Two teams maintaining separate data; parallel approval loops; duplicate reporting | "Which bucket should own this, and what should the other bucket stop doing?" |
| **WrongFunction** | Work is being performed by a function or role that is not the best fit | High-level manager doing transactional tasks; operational team making strategic decisions | "Is the current owner the right function, and if not, who should own it?" |
| **UnclearOwnership** | Ambiguous who is accountable — multiple parties share nominal ownership without clear decision rights | "Everyone owns it so nobody owns it"; escalations loop without resolution | "Who is the single accountable owner, and do they have authority to act?" |
| **ExcessCoordination** | Disproportionate cross-team coordination required, signaling boundary or process design issues | Weekly syncs for routine tasks; decisions requiring 4+ stakeholder sign-off | "What drives the coordination overhead, and how could this be restructured?" |

---

## Work Bucket Reference (19 Buckets)

### Purchasing (8 buckets)

#### B1: Supplier Sourcing & Qualification
- **Owner**: Procurement Manager
- **Owner Type**: Single
- **Flags**: Gap
- **Key Outputs**: Qualified supplier base; sourcing recommendations; supplier approvals
- **Notes**: Minimal effort currently expended towards supplier qualification; no quality involvement at the supplier level

#### B2: Material Qualification & Requirements Management
- **Owner**: Plant Quality | **Secondary**: Procurement Manager; Engineering
- **Owner Type**: Shared
- **Flags**: Boundary; WrongFunction; UnclearOwnership; Gap
- **Key Outputs**: Approved materials; qualification records; inspection standards
- **Notes**: PPAP coordination, customer-specific requirements flow-through. Messy boundary between Purchasing, Quality, and Engineering; Central governance of part qualification lacking

#### B3: Strategic Sourcing & Contract Management
- **Owner**: Procurement Manager
- **Owner Type**: Single
- **Flags**: Gap
- **Key Outputs**: Signed contracts; negotiated pricing; preferred supplier agreements
- **Notes**: Combines RFQ management, competitive bidding, contract negotiation, pricing agreements, cost optimization across all categories (direct, indirect, CapEx, tooling). Resources are shared with tactical, daily urgencies which take precedent leaving this bucket under supported.

#### B4: Supplier Performance Management
- **Owner**: Procurement Manager | **Secondary**: Plant Quality
- **Owner Type**: Shared
- **Flags**: Boundary; Duplication; Gap
- **Key Outputs**: Supplier scorecards; corrective action plans; audit outcomes
- **Notes**: Scorecards, SCARs, supplier development, corrective actions. Resources are shared with tactical, daily urgencies which take precedent leaving this bucket under supported. Duplication of systems between USA + MEX.

#### B5: Tactical Purchasing / Order Execution
- **Owner**: Procurement Manager | **Secondary**: Plant Planners
- **Owner Type**: Shared
- **Flags**: Duplication; WrongFunction
- **Key Outputs**: Issued purchase orders; confirmed deliveries; resolved discrepancies
- **Notes**: Day-to-day PO management for indirect, spot buys, service POs, and any direct materials that aren't planned releases. Duplication of request, approval, follow-up.

#### B6: Supply Chain Risk, Compliance & Requirements Flow-Down
- **Owner**: Procurement Manager
- **Owner Type**: Single
- **Flags**: Boundary; Duplication; Gap
- **Key Outputs**: Compliance reports; cascaded requirements; risk mitigation plans
- **Notes**: Customer-specific requirement cascading, conflict minerals, sustainability reporting, supplier risk assessments, business continuity, crisis/disruption response, tariff/regulatory impact. Duplication USA + MEX.

#### B7: Cost Administration & Transparency
- **Owner**: Procurement Manager | **Secondary**: Finance
- **Owner Type**: Single
- **Flags**: Boundary; Duplication; ExcessCoordination; WrongFunction
- **Key Outputs**: Standard cost updates; cost transparency reports; discrepancy resolutions
- **Notes**: Maintaining standards, communicating cost changes to finance & sales, quantifying them against our forecast, managing transparency process (MRB). Sales, Finance, Purchasing intersect. Too much coordination. Wrong function presiding over the process currently.

#### B8: Quoting & Estimating New Business (Materials, Outsourcing, Subcontracting)
- **Owner**: Procurement Manager | **Secondary**: Engineering; Sales
- **Owner Type**: Shared
- **Flags**: Boundary; ExcessCoordination; Duplication
- **Key Outputs**: Material cost estimates; quoted BOMs; TCO analysis
- **Notes**: Boundaries unclear with estimating department, work sometimes duplicated, excess discussion needed to minimize unnecessary work and turn in best work product.

---

### Logistics (3 buckets)

#### B9: Freight Management (Inbound & Outbound)
- **Owner**: Logistics Manager | **Secondary**: Plant Shipping
- **Owner Type**: Shared
- **Flags**: Boundary
- **Key Outputs**: Freight bookings; tracking updates; freight cost reports
- **Notes**: Carrier selection, rate negotiation, routing, freight cost optimization. Plants handle daily recurring, Logistics Manager handles strategic negotiation, partner selection, cost control, expedites and escalations

#### B10: Trade Compliance
- **Owner**: Logistics Manager | **Secondary**: Mexico Operations
- **Owner Type**: Shared
- **Flags**: Duplication
- **Key Outputs**: Cleared shipments; compliance filings; duty classifications
- **Notes**: USMCA/rules of origin, import/export documentation, customs, duty management, IMMEX compliance. Duplication between USA + MEX.

#### B11: Warehouse / Shipping / Receiving Operations
- **Owner**: Plant Warehouse Teams | **Secondary**: Logistics Manager
- **Owner Type**: Shared
- **Flags**: Boundary; UnclearOwnership
- **Key Outputs**: Received goods; shipped orders; warehouse inventory records
- **Notes**: Lacking central governance ownership. Listed Logistics Manager as secondary owner but current reality is there isn't clear ownership here.

---

### Planning & Inventory (3 buckets)

#### B12: Planning & Scheduling
- **Owner**: Plant Planners | **Secondary**: VP Supply Chain
- **Owner Type**: Shared
- **Flags**: UnclearOwnership; Boundary; ExcessCoordination
- **Key Outputs**: Production schedules; material delivery schedules; planned orders
- **Notes**: Recently shifted material planning from centralized to decentralized. Lacking corporate governance - Metrics; Standardization; Tools; parameters. Purchasing supports escalations / gaps / expedites.

#### B13: Inventory Policy & Optimization
- **Owner**: VP Supply Chain
- **Owner Type**: Single
- **Flags**: ExcessCoordination
- **Key Outputs**: Inventory targets; optimization recommendations; SMOI disposition
- **Notes**: Poor ownership currently; opportunity for clarity. Safety stock setting, reorder logic, slow-moving/obsolete management, inventory turns management. Not sure this is a second work bucket but intent is for previous bucket to be daily tactical work and this one to be strategic company wide ownership.

#### B14: Inventory Integrity & Control
- **Owner**: VP Supply Chain | **Secondary**: Plant Operations
- **Owner Type**: Shared
- **Flags**: UnclearOwnership
- **Key Outputs**: Reconciled inventory records; cycle count schedules; adjustment approvals
- **Notes**: Physical inventory, cycle counting, inventory accuracy, inventory control. Policy vs. execution split between corporate and plants.

---

### Customer Service (3 buckets)

#### B15: Order Management
- **Owner**: Plant Customer Service | **Secondary**: Plant Planners
- **Owner Type**: Shared
- **Flags**: Duplication; UnclearOwnership
- **Key Outputs**: Confirmed orders; scheduling system updates; customer acknowledgments
- **Notes**: Receiving and processing customer releases/forecasts, managing EDI, customer portals. Inconsistency between USA + MEX.

#### B16: Shipping & Delivery Execution
- **Owner**: Plant Customer Service
- **Owner Type**: Single
- **Flags**: UnclearOwnership
- **Key Outputs**: Shipped orders; ASNs; packing documentation
- **Notes**: Picking, packing, shipping to customer requirements, ASN generation, label compliance. Inconsistency between plants.

#### B17: Customer Communication & Issue Resolution
- **Owner**: Plant Customer Service | **Secondary**: Sales; Program Management
- **Owner Type**: Shared
- **Flags**: Duplication; ExcessCoordination
- **Key Outputs**: Customer responses; recovery plans; issue resolution records
- **Notes**: Responding to delivery inquiries, managing past-due situations, coordinating recovery plans.

---

### Cross / VP-Level (2 buckets)

#### B18: Supply Chain Data / Systems & Reporting
- **Owner**: VP Supply Chain | **Secondary**: IT; Finance
- **Owner Type**: Shared
- **Flags**: Boundary; Duplication; UnclearOwnership; WrongFunction; Gap
- **Key Outputs**: SC dashboards; system tools; performance reports
- **Notes**: Master data maintenance, ERP supply chain configuration, Power BI reporting, KPI development and analytics.

#### B19: Item Configuration / Raw Material Setup
- **Owner**: VP Supply Chain | **Secondary**: Engineering; Plant Operations
- **Owner Type**: Single
- **Flags**: Boundary; Duplication; UnclearOwnership; WrongFunction; Gap
- **Key Outputs**: Configured item masters; raw material setups; system-ready BOMs
- **Notes**: Maybe not a work bucket in itself but is a challenge area worth discussing.

---

## Carlos' Future-State Design (from Visio file)

### Design Philosophy
Carlos organized the COO span around three core value-creating work systems:

1. **Production Execution** → VP Operations (Pinar Sezgen)
2. **Industrialization** → VP Engineering & PM (Eric Uram)
3. **Supply Assurance** → VP Supply Chain (Gavin Simpson)

**Guiding Principles:**
- Each VP role owns a complete work system with measurable outcomes
- Organizational fragmentation that forces coordination must be minimized
- Decision rights must be clear and local — no cross-VP arbitration for routine tradeoffs
- If a function cannot own a full work system, it should not be a VP role
- Simplify the system, not cut muscle
- Scale by adding capacity inside systems, not new systems

### Future-State Supply Chain Org

**VP Supply Chain (Gavin Simpson)** — owns the "source and flow" work system end to end

> "Supply chain is a control tower function. It must make tradeoffs across plants, suppliers, and customers. Fragmenting it creates local optimization and excess inventory, which is pure SG&A leakage."

| Role | Workstream | Person | Carlos Notes |
|------|-----------|--------|-------------|
| VP Supply Chain | Source and Flow (end to end) | Gavin Simpson | Control tower function. Owns supplier strategy, inventory targets, material availability. |
| Purchasing Manager | Strategic Sourcing & Supplier Performance | Khris Cook | Inventory policy and tradeoffs, make vs buy, cross-plant allocation, priority arbitration. |
| Direct Buyer (resins/additives) | Category Execution | Jen Albrecht | Does not negotiate strategy or override contracts. Day-to-day execution. |
| Direct Buyer (components/outsourced) | Category Execution | Daniela Ojeda | Does not negotiate strategy or override contracts. Day-to-day execution. |
| CapEx & Indirect Buyer (global) | Indirect and Capital Procurement | Amanda Beeman | Vendor selection within policy, commercial execution. |
| Logistics Manager | Physical Flow & Transportation | Mike Quayle | Must be consolidated globally. Splitting by region inflates cost. |
| Foreign Trade Specialist (Mexico) | Trade Compliance Execution | Jesus Bolivar | Trade compliance execution, risk prevention. |
| Supply Planning & Inventory Manager | Inventory Planning & Availability | Martin Munoz | Critical role. Without it, Purchasing optimizes cost and Logistics optimizes freight while inventory balloons. |
| Planner USA | USA Planning Execution | Angelina Sagan | Does not set policy or targets. Executes planning rules, timely escalation. |
| Planner Mexico | Mexico Planning Execution | TBD | Does not set policy or targets. Executes planning rules, timely escalation. |

### Open Questions from Carlos (noted on Visio)
1. "Do these positions need to be centralized or do they land under the plant materials manager?" (referring to planners)
2. "Task: Clarify and then simplify the interaction between launch manager and program manager."
3. "Task: Metrology"

### Other Functions Under COO (for boundary awareness)

**VP Operations (Pinar Sezgen)** — owns the "make" work system end to end
- Director of Quality (Zach Parker), EH&S Manager (OPEN), CI Director (Georgina Arreola)
- Plant Managers: Maria Dorsey (Rochester), Jeff Lee (Shelbyville), Ryan Robinson (Pulaski), Chad Terrill (Middletown), Roberto Portillo (Chihuahua), Salvador Maldonado (Queretaro)

**VP Engineering & PM (Eric Uram)** — owns the industrialization work system
- Program Managers: Mike Bustamante, Maria McKinney, Sal Nicolosi
- Tooling Manager (OPEN), Processing & Automation: Mike Malone, Nick Pizzarello, Luis Marrufo
- Engineering Manager (Rob Powell) with Product Engineers: Wesley Barnes, Nick Pletz, Amelia Peer, Eric Eyestone

**VP BPE&T (Jorge Gutierrez)** — Process Mapping and Enterprise-Wide Transformation

---

## Deliverables

| File | Purpose |
|------|---------|
| `SC_Work_Bucket_Backup.xlsx` | Working Excel file — Bucket Reference, Flag Definitions, Carlos Future State Reference |
| `SC_Work_Bucket_Map.pptx` | Visual summary for workshop — pillar slides, issue density heat map, key observations |
| `workshop-project.md` | This file — full project context for continuity between sessions |

## Project Status

| Step | Description | Status |
|------|-------------|--------|
| 1 | Finalize work bucket list | **Complete** — 19 buckets across 5 pillars |
| 2 | Map current-state ownership | **Complete** — primary/secondary owners, owner type, flags |
| 3 | Flag issues | **Complete** — 6 flag types defined with workshop questions |
| 4 | Refine key outputs | **Complete** — standardized to noun-phrase style |
| 5 | Build workshop deliverable | **In Progress** — PowerPoint needs rebuild to match latest data |
| 6 | Current vs. future gap analysis (optional) | Not Started |
