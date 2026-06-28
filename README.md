System Master Specification and Technical README for Builders Stream Pro
Strategic Market Analysis and Positioning
The residential renovation and construction software sector in the United States is undergoing a structural transition driven by generational shifts, material price volatility, and rapid consolidation among enterprise software providers. Micro-contractors and small-scale remodeling firms employing between 1 and 50 workers represent an underserved segment within the broader construction technology landscape. These firms are caught in a technological gap between expensive enterprise-grade systems costing upwards of $20,000 annually and simple field-service tracking applications that lack construction financial features.   

Builders Stream Pro is a multi-tenant Software-as-a-Service platform built on Django, HTMX, and PostgreSQL. The system is designed to provide comprehensive, affordable, and renovation-focused project management features to this target segment.   

Market research indicates that the global construction software market reached a valuation of approximately $4.07 billion in 2025, with broader estimates extending to $7.67 billion when including adjacent building information modeling and enterprise resource planning integrations. The United States represents the largest single national market, valued at $0.98 billion to $1.11 billion in 2024, which accounts for 40.2% of the North American landscape. Within this domestic market, the small and mid-sized enterprise segment commands a 44.6% share, translating to an estimated $440 million to $500 million in Annual Recurring Revenue in 2025.   

The residential renovation and remodeling sub-niche, which serves as the primary target for Builders Stream Pro, represents $80 million to $120 million of this addressable market. This segment is the fastest-growing and most fragmented sub-segment in the industry.   

Market Sizing Level	US Market Valuation (2025 Baseline)	Percentage Share of Parent Segment	Historical and Projected CAGR	Data Confidence
Total Addressable Market (TAM)	~$1,100,000,000	
100.0% of Domestic Construction Tech 

8.00% – 10.00% Historical (2019–2024) 

High 

Serviceable Addressable Market (SAM)	~$450,000,000 – $500,000,000	
~44.6% of TAM (SME Construction Segment) 

11.06% Projected SME CAGR (2025–2030) 

Medium 

Serviceable Obtainable Market (SOM)	~$180,000,000 – $250,000,000	
~40.0% – 50.0% of SAM (1–50 Employee Firms) 

11.50% Projected Sub-Segment CAGR 

Medium 

Primary Renovation Niche Target	~$80,000,000 – $120,000,000	
~30.0% – 40.0% of SOM (SME Remodelers) 

12.00% – 14.00% Active Renovation CAGR 

Medium 

  
This market growth is driven by rising home renovation demand, supported by normalized interest rates, an aging domestic housing stock, and an influx of digital-native Gen Z and Millennial business owners. Historical data indicates a baseline 5-year CAGR of 8% to 10% from 2019 to 2024, which was accelerated by pandemic-era digital adoption. The broader construction project management software market is projected to reach $17.81 billion globally by 2031, representing a steady CAGR of 8.99%.   

The domestic SME sub-segment is growing even faster at 11.06% annually. This rapid expansion highlights a significant market opportunity as older, spreadsheet-reliant contractors hand off their businesses to a younger generation.   

Projected Calendar Year	Estimated Domestic SME Construction Software Market Size	Incremental Sector Expansion	Cumulative Strategic Growth
2025	$450,000,000 – $500,000,000	
Baseline 

Reference Year 

2026	$500,000,000 – $555,000,000	
+$50,000,000 to +$55,000,000 

Baseline Comparison 

2027	$555,000,000 – $615,000,000	
+$55,000,000 to +$60,000,000 

+$115,000,000 

2028	$615,000,000 – $680,000,000	
+$60,000,000 to +$65,000,000 

+$180,000,000 

2029	$680,000,000 – $755,000,000	
+$65,000,000 to +$75,000,000 

+$255,000,000 

2030	$755,000,000 – $840,000,000	
+$75,000,000 to +$85,000,000 

+$305,000,000 to +$340,000,000 

  
Industry Structure and Competitive Landscape
The construction technology market features highly concentrated ownership at the enterprise tier, but remains highly fragmented at the SME and micro-contractor levels. The top five software providers—Oracle, Autodesk, Procore, Trimble, and Bentley Systems—collectively captured approximately 45% of total industry revenue in 2025.   

In contrast, the SME and small contractor sub-segment remains highly fragmented, with the top five players controlling only 35% to 40% of the market. This fragmentation highlights a clear opening for a nimble, niche-focused competitor.   

Industry Player	Target Market Segments	Pricing Strategy and Cost Structure	Key Platform Strengths	Key Platform Weaknesses
Procore	
Large Commercial GCs ($50M+ Volume) 

$20,000 – $100,000+/year custom enterprise contracts.

Extensive feature set, strong developer APIs, and dominant commercial brand.

High cost, complex interface, and steep learning curve for small teams.

Buildertrend	
Residential Homebuilders and Remodelers 

$339 – $1,099/month, no free trial options.

Massive market share, broad residential feature set, and strong brand awareness.

High price points, poor data portability, and friction from the CoConstruct acquisition.

Autodesk Build	
Commercial GCs and Complex Infrastructure 

Enterprise seat-based licensing models.

Built-in BIM integrations and deep CAD file support.

Overly complex UI and high cost for light residential use cases.

JobTread	
Small GCs and Remodelers ($500K–$5M Volume) 

$159/month flat plus $18/user/month seat licensing.

Clean modern UI, high customer satisfaction, and flexible estimating.

Growing integration catalog and limited international language support.

Jobber	
Fast-Cycle Specialty Trade Services 

$39 – $149/month tiered subscription models.

Intuitive mobile UI and fast job scheduling capabilities.

Lacks support for complex multi-phase pricing and document workflows.

Housecall Pro	
Residential Home Services 

$49 – $149/month tiered subscription models.

Integrated invoicing and scheduling for dispatch teams.

Not designed to support multi-phase renovation and budget workflows.

Contractor Foreman	
Cost-Sensitive Small Contractors 

$49 – $415/month tiered subscription models.

Highly affordable entry point with a broad feature set.

Clunky interface and slower development cycles.

CoConstruct	
Custom Homebuilders (Legacy Platform) 

Discontinued legacy rates; migrated to Buildertrend.

Strong legacy design for custom home workflow coordination.

Abandoned codebase with zero feature updates since 2021.

  
This market structure highlights several key entry barriers for new software platforms. High customer acquisition costs and the difficulty of building trust with risk-averse contractors present significant challenges for new market entrants.   

Entry Barrier Category	Market Threat Level	Practical Entry Barriers and Technical Constraints
Distribution and CAC	High	
Reaching a highly fragmented base of 3.9 million small contractors is expensive. Marketing relies heavily on review directories, trade events, and organic word-of-mouth.

Brand and Operational Trust	Medium to High	
Small builders are highly risk-averse. They rely on reviews from trusted directories like G2 and Capterra to verify software reliability.

Data Lock-in and Migration	Medium	
Major players deliberately restrict data exports. New platforms must offer easy, white-glove data migration to win over switching users.

Integrations and Ecosystem	Medium	
Seamless, certified integrations with QuickBooks Online and processing platforms are table stakes for modern workflows.

Network Effects	Medium	
Client portals and subcontractor collaboration loops create minor switching barriers, though they are not insurmountable.

Technology and Product Core	Medium	
Standard features are well understood. Strategic advantages come from mobile-first PWAs and modern frontend experiences.

Regulatory and Compliance	Low	
Standard consumer data privacy laws (like CCPA and GDPR) apply, but the industry lacks complex, sector-specific federal software certifications.

  
Macro-Economic and Environmental Drivers
The structural shifts in the residential construction and remodeling sectors are driven by several macro and micro trends, which are analyzed below using a structured PESTEL framework.   

PESTEL Dimension	Key Macro and Micro Environmental Drivers	Direct Strategic Impact on Builders Stream Pro
Political	
Federal infrastructure programs supply capital to large commercial construction, which draws enterprise software providers upmarket and away from the SME segment.

Highly Favorable. The enterprise focus on large-scale infrastructure projects leaves the SME residential renovation space open and underserved.

Economic	
Rising interest rates and home affordability constraints lead homeowners to renovate their current properties rather than buy new ones, while rising material costs squeeze builder margins.

Highly Favorable. Margin compression increases demand for cost-tracking and job-costing software to protect project profitability.

Social	
Tech-savvy Gen Z and Millennial business owners are replacing retiring contractors, bringing high expectations for mobile-first, easy-to-use software.

Highly Favorable. The generational transition accelerates the shift away from manual processes to modern, mobile-friendly platforms.

Technological	
Cloud-native hosting is now the industry standard, and fast frontend tools like HTMX and Alpine.js make it easy to build highly responsive, mobile-first web apps.

Highly Favorable. Modern frontend tools allow a solo developer to build a fast, responsive application without the overhead of heavy JavaScript frameworks.

Environmental	
Green building regulations and material sustainability mandates increase the tracking complexity of residential renovations.

Long-term Opportunity. Green building certifications can be packaged as premium add-on modules in later product phases.

Legal	
Domestic consumer privacy standards, such as California's CCPA, impose strict rules on client data storage and deletion.

Low Threat. Builders Stream Pro implements automated CCPA data erasure protocols from day one to ensure compliance.

  
Customer Personas and Purchasing Deciders
Builders Stream Pro targets three primary customer personas, each with distinct pain points and software budgets.   

Persona A: Marcus — "The Scaling General Contractor"
Marcus represents the primary target profile. He manages an eight-person remodeling firm generating $1.8 million in annual revenue in the Sun Belt.   

Operational Dynamics: Marcus spends his days traveling between job sites and managing customer communications. He relies on Excel for estimating and uses QuickBooks for basic bookkeeping.   

Key Pain Points: Marcus loses $40,000 to $80,000 in gross margin annually due to manual estimating errors and unrecorded verbal change orders. He is currently paying $499 per month for Buildertrend, but feels he is overpaying for a complex system he barely uses.   

Budget Constraints: Marcus is willing to pay up to $300 to $600 per month for software, but requires clear ROI and a free trial to evaluate usability.   

Persona B: Lisa — "The Solo Renovator"
Lisa represents the secondary target profile. She runs a kitchen-and-bath remodeling company with three employees, generating $480,000 in annual revenue.   

Operational Dynamics: Lisa manages design work and client selections. She currently uses Jobber for dispatch, alongside Google Sheets and her mobile camera.   

Key Pain Points: Lisa struggles with tax-season bookkeeping and client disputes due to disorganized project records. She finds field-service tools like Jobber lack the financial tracking needed for complex remodeling projects.   

Budget Constraints: Highly price-sensitive, Lisa has a strict budget ceiling of $50 to $150 per month and will only convert if the software runs smoothly on her mobile device.   

Persona C: Derek — "The CoConstruct Refugee"
Derek represents a highly motivated, high-value acquisition opportunity. He runs a custom home renovation firm with 22 employees, generating $4.5 million in annual revenue.   

Operational Dynamics: Derek ran his operations on CoConstruct for years. Since Buildertrend acquired the platform and stopped developing it, he has been looking for a modern alternative.   

Key Pain Points: Derek is frustrated by clunky interfaces and forced migrations. He is actively evaluating new tools to find a modern, reliable platform.   

Budget Constraints: Willing to pay $500 to $1,500 per month, Derek prioritizes system reliability, data portability, and a smooth migration experience.   

Technical Architecture and Row-Level Multi-Tenancy
Builders Stream Pro uses a row-level multi-tenancy model, where all customer data is stored in a single PostgreSQL database. This architecture avoids the deployment and maintenance overhead of managing separate database schemas for each tenant, making it ideal for a lean development team.   

Incoming Request (acme.buildersstream.pro)
           │
           ▼
┌────────────────────────────────────────────────────────┐
│ TenantMiddleware                                       │
│  1. Parse host: acme.buildersstream.pro                │
│  2. Fetch Tenant (slug='acme', is_active=True)         │
│  3. Bind Tenant to thread-local storage                │
└────────────────────────────────────────────────────────┘
           │
           ▼
┌────────────────────────────────────────────────────────┐
│ TenantManager (get_queryset)                           │
│  1. Intercept query: Project.objects.all()             │
│  2. Inject filter:.filter(tenant=current_tenant)      │
└────────────────────────────────────────────────────────┘
           │
           ▼
┌────────────────────────────────────────────────────────┐
│ PostgreSQL 16                                          │
│  - Executes query isolated to 'acme' database rows     │
└────────────────────────────────────────────────────────┘
The system uses a three-layer defense to guarantee complete multi-tenant data isolation :   

Python
# bsp/utils.py
import threading

_thread_locals = threading.local()

def set_current_tenant(tenant):
    """Bind the active tenant instance to thread-local storage."""
    _thread_locals.current_tenant = tenant

def get_current_tenant():
    """Retrieve the active tenant instance from thread-local storage."""
    return getattr(_thread_locals, 'current_tenant', None)

def clear_current_tenant():
    """Clear the tenant instance to prevent cross-thread contamination."""
    if hasattr(_thread_locals, 'current_tenant'):
        del _thread_locals.current_tenant
Every model representing tenant-specific data must include objects = TenantManager() as its default manager and declare a foreign key link to the root Tenant record.   

Complete Database Schema and Model Definitions
The physical data model for the Builders Stream Pro database consists of structured tables linked via explicit foreign key relationships. Primary keys are systematically generated as Universally Unique Identifiers (UUIDv4) to prevent enumeration attacks and secure public client URLs.   

Tenant Model
The root entity of the system database. It represents an individual contractor firm.   

Field	Data Type	Nullable	Relational and Validation Rules
id	UUID	No	
Primary Key; default is generated using uuid4.

name	Varchar(120)	No	
Company display title, e.g., 'Acme Renovation LLC'.

slug	Slug(50)	No	
Unique index; acts as the DNS routing subdomain.

plan_tier	Varchar(20)	No	
ENUM constraint: personal | business | enterprise.

qb_realm_id	Varchar(50)	Yes	
Identifies connected company in QuickBooks Online.

qb_access_token	Varchar(255)	Yes	
Encrypted at rest using django-encrypted-model-fields.

qb_refresh_token	Varchar(255)	Yes	
Encrypted at rest; rotated on every API access.

qb_token_expiry	DateTime	Yes	
Access token TTL (1 hour); refresh token TTL (101 days).

is_active	Boolean	No	
Suspends application access if toggled to False.

created_at	DateTime	No	
Automated initialization timestamp.

  
User Model
This table extends Django's AbstractBaseUser class, substituting email addresses as the default login identifier.   

Field	Data Type	Nullable	Relational and Validation Rules
id	UUID	No	
Primary Key.

tenant	ForeignKey	No	
Cascades on delete; index is enforced.

email	Email	No	
Unique index constrained by: unique_together=[tenant, email].

role	Varchar(20)	No	
ENUM: owner (billing access) | project_manager | field_crew | viewer.

is_active	Boolean	No	
Disables active session initiation without purging historic records.

last_login	DateTime	Yes	
Tracked to identify accounts at risk of churning.

  
Project Model
The core entity around which all estimating, costing, and invoicing operations revolve.   

Field	Data Type	Nullable	Relational and Validation Rules
id	UUID	No	
Primary Key.

tenant	ForeignKey	No	
Scopes the project to a specific tenant; index is active.

client	ForeignKey	No	
Resolves to the Client record; safe deletion uses SET_NULL.

project_manager	ForeignKey	Yes	
Resolves to User; unassigned records are permitted.

name	Varchar(200)	No	
Informational label, e.g., 'Henderson Kitchen Remodel 2027'.

status	Varchar(20)	No	
ENUM: lead (default) | active | on_hold | completed | cancelled.

phase	Varchar(30)	No	
ENUM: scope | demo_discovery | revised_scope | rough_in | finishes | punch_list | closeout.

budget	Decimal(12,2)	Yes	
Approved contract value; compared with actual logged costs.

address	Varchar(300)	Yes	
Job site location physical address.

start_date	Date	Yes	
Actual project start date.

estimated_end_date	Date	Yes	
Populates the estimated timeline in the Client Portal.

  
Estimate and EstimateLineItem Models
A project may carry multiple versioned estimates to preserve historical budget projections.   

Field (Estimate)	Data Type	Nullable	Relational and Validation Rules
id	UUID	No	
Primary Key.

project	ForeignKey	No	
Cascades on delete; index is active.

status	Varchar(20)	No	
ENUM: draft | sent | approved | rejected | superseded.

total_amount	Decimal(12,2)	No	
Denormalized sum of estimate line items; updated via database signals.

version	Integer	No	
Auto-incremented count, displayed as 'Rev 2'.

  
Field (LineItem)	Data Type	Nullable	Relational and Validation Rules
id	UUID	No	
Primary Key.

estimate	ForeignKey	No	
Cascades on delete; index is active.

category	Varchar(50)	No	
ENUM: labor | materials | subcontractor | equipment | permit | other.

description	Text	No	
Line item description of work.

quantity	Decimal(10,3)	No	
Precision accommodates structural linear and volume units.

unit_cost	Decimal(10,2)	No	
Direct cost baseline before contractor markup.

markup_pct	Decimal(5,2)	No	
Pulled from Tenant defaults; overridable per line.

total	Decimal(12,2)	No	
Calculated as: quantity×unit_cost×(1+ 
100
markup_pct
​
 ).

sort_order	Integer	No	
Sequences visual presentation inside interactive interface.

  
ChangeOrder Model
Manages project scope extensions and calculates their impact on the approved baseline budget.   

Field	Data Type	Nullable	Relational and Validation Rules
id	UUID	No	
Primary Key.

project	ForeignKey	No	
Cascades on delete.

number	Integer	No	
Auto-incremented sequential count scoped per project.

status	Varchar(20)	No	
ENUM: draft | sent | approved | rejected | voided.

amount	Decimal(12,2)	No	
Direct value adjustment; negative values indicate system credits.

signature_token	Varchar(64)	Yes	
Secure, single-use token embedded in email links.

signed_at	DateTime	Yes	
Null until the homeowner executes approval.

client_ip	GenericIP	Yes	
Captured at signature execution to provide an audit trail.

  
Invoice Model
Tracks milestone and progress billings generated within individual projects.   

Field	Data Type	Nullable	Relational and Validation Rules
id	UUID	No	
Primary Key.

project	ForeignKey	No	
Cascades on delete.

number	Integer	No	
Auto-incremented database count scoped per tenant.

status	Varchar(20)	No	
ENUM: draft | sent | viewed | partial | paid | overdue | voided.

amount	Decimal(12,2)	No	
Total face value of the billing record.

qb_invoice_id	Varchar(50)	Yes	
Holds QuickBooks Online primary key after sync.

qb_sync_status	Varchar(20)	No	
ENUM: pending | synced | error | skipped.

due_date	Date	Yes	
Fallback maps to immediate payment terms.

paid_at	DateTime	Yes	
Synchronized via QuickBooks webhook execution.

  
Supporting Model Summary
To keep database queries fast and preserve clear records for audit trails, the platform schema includes several supporting tables :   

Supporting Model	Key Structural Design and Audit Trail Parameters	Active Database Indexes
Client	
Homeowner profile database. One client can have multiple projects.

tenant_id, email.

Task	
Checklist items mapped to project phases. Supports UI sorting.

project_id, sort_order.

DailyLog	
Daily logs capturing crew counts, hours worked, weather, and text notes. Daily logs become immutable 7 days after entry.

project_id, date.

Photo	
Maps images stored in S3 to projects. Supports visibility toggles for the Client Portal.

project_id, uploaded_by_id.

TimeEntry	
Captures labor hours worked by field crews, which are multiplied by hourly rates for job costing.

project_id, user_id, date.

ClientPortalToken	
Generates secure, token-based links for client portals to bypass password logins.

token, is_active.

QBSyncLog	
Logs integration payloads, response codes, and error details for QuickBooks Online.

tenant_id, entity_type, entity_id.

Subscription	
Tracks subscription states and customer accounts synced from Stripe.

tenant_id, stripe_subscription_id.

  
Core Product Requirements and MVP Boundaries
The Builders Stream Pro MVP is engineered to launch with a focused, highly reliable set of core modules, deferring complex features to keep development lean.   

Operational Parameter	In-Scope MVP Features	Explicitly Deferred Features (Post-MVP)
Project Financials	
Milestone invoices, expense logs, manual cost categories, and manual estimate building.

AI-assisted estimating, automatic material calculations, and digital lien waivers.

Accounting Integration	
Bidirectional sync with QuickBooks Online for invoices and clients.

Integrations with other accounting systems like Xero or Sage.

Document Signing	
Token-based change order approvals using typed-name digital signatures.

Direct integrations with third-party document tools like DocuSign.

Task Scheduling	
Milestones tied to the 7 renovation phases.

Gantt charts, interactive calendar views, and critical path scheduling.

Mobile Access	
Installable, offline-capable Progressive Web App (PWA).

Native iOS and Android applications.

Sub Collaboration	
Shared read-only public links for on-site subcontractors.

Dedicated logins and portals for subcontractors.

Multi-Tenancy	
Individual tenant subdomains.

Shared multi-company or franchise accounts.

  
7-Phase Renovation Lifecycle Implementation
Builders Stream Pro organizes project scheduling around the seven physical phases of a typical home renovation, keeping both the contractor and homeowner aligned.   

Renovation Phase	Active Contractor Tasks	Homeowner Experience	System Features Active
1. Scope	
Conducting site visits, taking baseline photos, and drafting the initial estimate.

Receives a secure portal link on Day 1.

Project creation, Client Portal invite, Estimating.

2. Demo & Discovery	
Demolition begins, often revealing hidden structural issues.

Views daily logs and photos documenting physical discoveries.

Daily logging, Photo feeds, Change orders.

3. Revised Scope	
Drafts a revised estimate reflecting on-site discoveries.

Reviews and signs off on updated budgets in the portal.

Estimating (V2), Change order signatures.

4. Rough-In	
Trades complete framing, plumbing, electrical, and HVAC rough-ins.

Tracks visual progress and milestones in the portal.

Daily logs, Time tracking, Milestone invoices.

5. Finishes	
Trades install drywall, flooring, trim, and fixtures.

Approves selections and reviews progress invoices.

Selections tracking, Progress invoicing.

6. Punch List	
Walks the job site to note and resolve outstanding issues.

Reviews the punch list and confirms completed items.

Task checklists, Punch lists, Portal updates.

7. Close-Out	
Submits final invoices and logs project profitability.

Pays final bills and receives project completion files.

Final invoicing, QuickBooks sync, Job Costing.

  
Functional Requirements: Module Specifications (M1 - M8)
The system is organized into eight functional modules, each governed by specific user stories and acceptance criteria.   

Module 1: Authentication and Tenant Onboarding
Operational Intent: Contractors must be able to sign up, configure their profiles, and create their first project in under 10 minutes.   

Strategic Strategy: Rather than forcing users through a rigid onboarding wizard, the app displays a clear checklist they can complete at their own pace.   

ID	User Stories	Target Acceptance Criteria (AC)
M1-S1	
As a contractor, I want to sign up with my email and password so I can quickly set up my company account.

AC-1: Registration completes in under three clicks. No credit card required for free trials.

M1-S2	
As an owner, I want to invite team members by email so I can delegate tasks.

AC-2: Invitation emails deliver in under 60 seconds. Links expire after 72 hours.

M1-S3	
As an owner, I want to restrict user access by role to secure my financial data.

AC-3: Field crew accounts are blocked from accessing billing, invoicing, and system settings.

M1-S4	
As an owner, I want to connect QuickBooks Online so my financial data syncs automatically.

AC-4: QuickBooks OAuth flow completes inside the app and displays connection and sync statuses.

  
Registration Form Submitted
           │
           ▼
Verify Email (Link expires in 72 hours)
           │
           ▼
Create Tenant Instance (Generate UUID and Schema ID)
           │
           ▼
Initialize Dashboard with Dismissible Checklist
  ├── 1. Add company logo and default markup
  ├── 2. Create first project
  ├── 3. Connect QuickBooks Online via OAuth
  └── 4. Invite first team member
Module 2: Project and Phase Management
Operational Intent: The project list is the primary interface for contractors and must load quickly, displaying current statuses and budget tracking at a glance.   

ID	User Stories	Target Acceptance Criteria (AC)
M2-S1	
As a contractor, I want to quickly create projects with basic details to begin tracking work.

AC-1: Project list loads in under 1.5 seconds for portfolios with 50 active projects.

M2-S2	
As an owner, I want to update project phases to keep the client portal in sync.

AC-2: Updating a project phase triggers client notifications and logs updates in the portal.

M2-S3	
As a PM, I want to track project budget states at a glance to avoid cost overruns.

AC-3: Budget indicators (Green/Yellow/Red) recalculate within 30 seconds of any logged expense.

  
Required Dashboard Fields: Project cards must clearly display: Project and Client Names, Current Phase Pill, Budget Health Indicator (Green: under 90%, Yellow: 90% to 100%, Red: over budget), Last Log Date, and Open Change Order Count.   

Module 3: Estimating
Operational Intent: Estimating is the primary feature valued by contractors. The estimator tool must be fast and intuitive, allowing contractors to build estimates on site.   

ID	User Stories	Target Acceptance Criteria (AC)
M3-S1	
As a contractor, I want to build line-item estimates with labor and material markups.

AC-1: A standard 25-line estimate can be built from scratch in under 15 minutes.

M3-S2	
As a contractor, I want to save line items as templates to reuse on future projects.

AC-2: Template searches return results in under 500ms for libraries of up to 100 templates.

M3-S3	
As a contractor, I want to share estimates with clients via portal links or PDFs.

AC-3: Mobile estimate layouts scale cleanly down to 375px widths without horizontal scrolling.

  
[Estimator UI]
  ├── Inline Line-Item Inputs (Category, Description, Qty, Unit, Unit Cost, Markup)
  ├── Drag-and-Drop Category Reordering
  ├── Dynamic Total Calculation (Cost, Markup, Total Sell Price)
  ├── Template Library (One-Click Save to Local Library)
  └── Version Control Engine
        ├── [Approved V1] - Set to Read-Only
        └── - Clones V1 items into V2 Draft
Line Item Calculation Formula: Estimate line-item calculations use decimal precision to prevent float-rounding errors:

Line Cost=Quantity×Unit Cost
Markup Value=Line Cost×( 
100
Markup Percentage
​
 )
Line Sell Total=Line Cost+Markup Value
Module 4: Change Order Management
Operational Intent: The change order tool helps contractors secure and document out-of-scope work, capturing homeowner signatures digitally.   

ID	User Stories	Target Acceptance Criteria (AC)
M4-S1	
As a contractor, I want to draft change orders with photos to document scope additions.

AC-1: Change orders can be created and sent in under 3 minutes.

M4-S2	
As a client, I want to sign change orders on my phone without needing to log in.

AC-2: Public signature links load on mobile browsers without requiring logins or app downloads.

M4-S3	
As a contractor, I want approved change orders to automatically update the project budget.

AC-3: Approved change order values update the baseline budget within 60 seconds.

  
Contractor: Creates Change Order
           │
           ▼
Generate signature_token (URL: /co/<token>/)
           │
           ▼
Email Client with Link
           │
           ▼
Homeowner opens link and reviews Change Order on Mobile
           ├── -> Reopen with comments
           └── [Action: Approve Change Order]
                 ├── Types Full Name as Signature
                 └── Captures timestamp, signature name, and IP address
                       │
                       ▼
Update Change Order status to "Approved"
           │
           ▼
Add approved value to Project.budget_approved_total
           │
           ▼
Send email confirmation to Client and Contractor
Module 5: Client Portal
Operational Intent: The portal provides homeowners with real-time updates, helping to reduce phone call inquiries by 60% to 70%. Access is link-based, requiring no password login.   

ID	User Stories	Target Acceptance Criteria (AC)
M5-S1	
As a homeowner, I want to track project timelines and phases to stay informed.

AC-1: Portal loads in under 2 seconds over 3G, with touch targets sized at ≥44px.

M5-S2	
As a homeowner, I want to view daily progress photos shared by the contractor.

AC-2: Toggling a photo's visibility setting updates the client portal instantly.

M5-S3	
As a contractor, I want to revoke portal links if a project enters a dispute.

AC-3: Revoking a portal token disables old links and generates a new, secure URL.

  
Required Portal Views: Project Overview and Phase Timeline, Filterable Photo Feed, Approved Change Orders, Invoices and Payment Schedules, and a Message Contractor contact form.   

Module 6: Invoicing and QuickBooks Sync
Operational Intent: Allows contractors to draft milestone invoices and sync financial records with QuickBooks Online.   

ID	User Stories	Target Acceptance Criteria (AC)
M6-S1	
As a contractor, I want to generate invoices from estimates or milestone progress.

AC-1: Invoice creation triggers a background sync to QuickBooks Online within 60 seconds.

M6-S2	
As a contractor, I want to check receivables and overdue billings across projects.

AC-2: The Receivables dashboard loads in under 2 seconds, displaying aging payment buckets.

M6-S3	
As an owner, I want QBO payment statuses to update automatically in BSP.

AC-3: QuickBooks webhooks process instantly, marking local invoices as paid.

  
BSP Invoice Created
           │
           ▼
Celery Worker: Queue Sync Job
           │
           ▼
Verify qb_invoice_id exists
  ├── -> Update Invoice in QBO (Check status is not Paid)
  └── [No]  -> Create Invoice in QBO (Store returned qb_invoice_id)
Module 7: Job Costing Dashboard
Operational Intent: Provides contractors with real-time project profitability calculations.   

ID	User Stories	Target Acceptance Criteria (AC)
M7-S1	
As an owner, I want to track project expenses against estimates to monitor margins.

AC-1: Budget health indicators recalculate within 30 seconds of logging a new expense.

M7-S2	
As a field PM, I want to upload receipt photos to log project expenses.

AC-2: Uploading an expense receipt takes less than 60 seconds via mobile browsers.

M7-S3	
As an owner, I want to restrict financial margin views to administrators.

AC-3: The field crew role is blocked from viewing financial summaries and margins.

  
Job Costing Calculations: Project financial margins are calculated using decimal precision:

Approved Contract Value=Approved Estimate Total+∑Approved Change Orders
Actual Labor Cost=∑(TimeEntry Hours×User Hourly Rate)
Total Actual Cost=Actual Labor Cost+Actual Materials+Actual Subcontractors+Actual Permits
Gross Margin Percentage=( 
Approved Contract Value
Approved Contract Value−Total Actual Cost
​
 )×100%
Module 8: Field Operations (Daily Logs and Time Tracking)
Operational Intent: Daily logging and time tracking must be fast and easy for field crews to complete on site, even with spotty cellular service.   

ID	User Stories	Target Acceptance Criteria (AC)
M8-S1	
As a crew member, I want to submit daily logs and photos from my mobile device.

AC-1: Submitting a daily log with photos takes under 2 minutes over 4G.

M8-S2	
As a crew member, I want to log my work hours while offline on remote job sites.

AC-2: Offline submissions queue locally and sync automatically when internet is restored.

M8-S3	
As a PM, I want to upload high-resolution progress photos directly to project files.

AC-3: S3 photo uploads bypass the application server, accepting files up to 15MB.

  
Required Log Fields: Project Link, Calendar Date (defaults to current date), Crew Count, Hours Worked, Work Performed Notes, Weather Conditions (Optional), and Progress Photos.   

Non-Functional Requirements and Security Constraints
Builders Stream Pro enforces strict performance, accessibility, and security guidelines to ensure a reliable enterprise-grade platform :   

Performance Standards: Pages must load in under 1.5 seconds on desktop and under 2.5 seconds over 3G mobile connections. Invoice synchronizations with QuickBooks Online must complete in under 60 seconds.   

Security Controls: Database queries filter results using TenantManager to prevent cross-tenant data leaks. Form submissions require CSRF verification, and QuickBooks integration tokens must be encrypted at rest using django-encrypted-model-fields. Public portal and signature links use secure, expiring tokens.   

Uptime and Backups: The platform targets a 99.5% monthly uptime SLA, backed by automated monitoring. PostgreSQL databases run daily automated backups with 7-day retention and point-in-time recovery enabled. File uploads in S3 use versioned buckets to prevent data loss.   

Accessibility and CCPA Compliance: Critical workflows, such as estimate builders and change order signatures, comply with WCAG 2.1 AA accessibility guidelines. To comply with CCPA standards, the platform includes automated data erasure endpoints to purge a tenant's historical records within 30 days upon request.   

Open Technical and Product Decisions
Several technical and product decisions remain open, with designated owners and targets for resolution before build starts :   

ID	Open Technical or Product Question	Designated Owner	Resolution Target
OQ-1	
Does the typed-name signature method for change orders meet all state contracting laws? 

Douglas Davis (Legal Consultation).

August 1, 2026.

OQ-2	
Should client-facing credit card payments via Stripe be included in the MVP launch scope? 

Douglas Davis (Product Strategy).

August 15, 2026.

OQ-3	
What level of task and milestone scheduling is required for the initial MVP? 

Douglas Davis (Product Design).

August 15, 2026.

OQ-4	
Should the entry-level Personal plan include feature gates to encourage upgrades? 

Douglas Davis (Pricing Strategy).

September 1, 2026.

OQ-5	
Should a basic material selections tracker be included in the MVP launch? 

Douglas Davis (Product Design).

September 1, 2026.

  
Platform Unit Economics and Pricing Models
Builders Stream Pro targets highly capital-efficient unit economics, using organic content marketing and direct referral partnerships to maintain low customer acquisition costs.   

Blended Monthly ARPU=$81
Target Monthly Churn=3.0%
Expected Customer Lifetime (L)= 
0.03
1
​
 ≈33.3 months
Projected Customer Lifetime Value (LTV)=33.3×$81≈$2,673
Target Customer Acquisition Cost (CAC)=$300−$500
Optimistic LTV:CAC Ratio= 
$300
$2,673
​
 ≈8.9:1
Conservative LTV:CAC Ratio= 
$500
$2,673
​
 ≈5.3:1
Projected Infrastructure Margin≈87%
This financial profile allows the platform to achieve early profitability, with subscription revenue covering infrastructure and operating costs at 75 active users.   

Quarterly Financial Forecasts (Year 1 - Year 3)
The platform's three-year financial plan outlines projected revenues, operational costs, and hiring plans.   

Year 1: Quarterly Projections (2027)
Financial Metric	Q1 2027	Q2 2027	Q3 2027	Q4 2027
New Customer Registrations	
20 

30 

40 

45 

Monthly Churned Customers	
2 

4 

6 

8 

Ending Paid Customers	
18 

44 

78 

115 

Quarterly Net Revenue	
$2,025 

$6,975 

$13,725 

$21,825 

AWS Infrastructure Costs	
$1,350 

$1,800 

$2,100 

$2,700 

Third-Party Subscriptions	
$600 

$600 

$600 

$600 

Marketing and Events	
$1,200 

$1,500 

$1,500 

$1,500 

Legal & Administrative Fees	
$1,500 

$300 

$300 

$300 

Customer Success Contractor	
$0 

$0 

$5,400 

$6,000 

Founder Salary Draw	
$0 

$0 

$7,500 

$10,000 

Total Quarterly Expenses	
$4,650 

$4,200 

$17,400 

$21,100 

Net Profit / (Loss)	
($2,625) 

$2,775 

($3,675) 

$725 

  
Year 1 Financial Summary: Total Revenue: $44,550, Total Expenses: $47,350, Net Operational Loss: ($2,800). The $10,000 in initial bootstrap capital covers the minor cash deficits in Q1 and Q3, paving the way for steady profitability in Year 2.   

Year 2: Financial Summary (2028)
Operational Baseline: The year starts with 115 customers and exits with 380, maintaining a blended ARPU of $83 per month as users upgrade tiers.   

Projected Revenues: Annual recurring subscription revenues are projected to reach $247,000.   

Projected Expenses: Total operating expenses are estimated at $198,000. This includes $28,000 for S3 and server infrastructure, $42,000 for organic content and SEO, $38,000 for a half-time customer success coordinator, $55,000 to hire a second developer for half the year, $80,000 for the founder's salary, and $18,000 for legal and administrative costs.   

Net Annual Profit: Net operational profit is projected at $49,000.   

Year 3: Financial Summary (2029)
Operational Baseline: The year starts with 380 customers and exits with 820, with blended ARPU rising to $88 per month as more users upgrade to the Enterprise tier.   

Projected Revenues: Annual subscription revenues are projected to reach $634,000.   

Projected Expenses: Total operating expenses are estimated at $410,000. This budget covers the developer team, increased cloud infrastructure, expanded marketing, and customer support.   

Net Annual Profit: Net operational profit is projected to reach $224,000.   

Go-To-Market and Pre-Launch Execution Roadmap
Builders Stream Pro targets 5 key marketing and acquisition channels to secure early users and grow cost-effectively :   

Customer Acquisition Channel	Key Launch Actions	Target Customers	Estimated Cost
CoConstruct Migration	
Build a migration landing page, offer free 1-click data imports, run direct outreach in builder communities, and offer white-glove onboarding.

Customers 1–40.

Founder Time.

BCK Construction Network	
Tap into personal networks in Texas, offer 6 months free in exchange for Capterra reviews, and ask for referrals.

Customers 1–25.

$1,000 in local events.

Content SEO & YouTube	
Publish two YouTube videos per month and weekly blog posts targeting terms like "Buildertrend alternative" and "remodeling estimating software".

Customers 25–70.

$100/month for SEO tools.

Capterra Review Seeding	
Target 50 G2 and 50 Capterra reviews by Month 6, using in-app prompts and direct email outreach to successful users.

Network Multiplier.

Free.

QuickBooks ProAdvisors	
Build referral partnerships with local bookkeepers, offering a $100 referral fee for every contractor client who signs up.

Customers 70–100+.

$100 per paid signup.

  
The platform's pre-launch timeline details the weekly milestones leading to the Q1 2027 public launch.   

Q4 2026: Pre-Launch Marketing and Beta Program
[October 2026: Foundation]
  ├── Week 1: Launch landing page with email waitlist form
  ├── Week 2: Open YouTube channel and post founder backstory video
  ├── Week 3: Engage in online construction and contractor communities
  └── Week 4: Select 20 beta prospects from BCK Construction network


  ├── Week 5: Attend regional NARI trade events to gather product feedback
  ├── Week 6: Publish SEO blog comparing remodeling and general construction software
  ├── Week 7: Conduct 1:1 platform demos with 10 committed beta prospects
  └── Week 8: Deliver beta invitations and open the feedback Slack channel (Nov 30)


  ├── Week 9: Survey beta users to categorize, prioritize, and resolve bugs
  ├── Week 10: Configure production Stripe billing and G2/Capterra profiles
  ├── Week 11: Send priority soft-launch invites to waitlist subscribers
  └── Week 12: Run final automated performance audits and lock Jan 15 soft launch
Q1 2027: Soft Launch to Public Scale

  ├── Week 1: Onboard the 50 BCK network waitlist signups with a 3-month free offer
  ├── Week 2: Resolve early user bugs and run direct support calls with active users
  ├── Week 3: Post the first full platform walkthrough video on YouTube
  └── Week 4: Deploy the "CoConstruct Migration" landing page and import tool

[February 2027: Public Launch]
  ├── Week 5: Run personal outreach calls with trial signups who haven't created projects
  ├── Week 6: Send automated prompts to collect the first 10 G2 and Capterra reviews
  ├── Week 7: Publish change order video targeting "remodeling change order template"
  └── Week 8: Complete QuickBooks Developer certification to earn the certified partner badge


  ├── Week 9: Run outreach campaigns targeting trials ending without conversions
  ├── Week 10: Publish "Buildertrend vs. Builders Stream Pro" comparison blog
  ├── Week 11: Launch simple, in-app referral program offering free billing credits
  └── Week 12: Run Q1 review to count paying users and prioritize the Q2 roadmap
Operational Risk Mitigation Framework
The platform monitors five key strategic risks, with mitigation plans and pivot triggers established for each.   

Strategic Risk	Severity	Mitigation Plan	Quantitative Pivot Trigger
Market Consolidation (JobTread dominates SME segment).

High	
Maintain focus on home remodeling workflows, avoiding general general contractor features.

If JobTread adds remodeling templates before launch, pivot to target kitchen-and-bath niches.

Product-Market Fit Failure (High user churn).

Existential	
Onboard the first 50 users manually, collect weekly feedback, and prioritize stability over features.

If weekly active usage drops below 60% in Month 3, pause marketing to audit user sessions.

QuickBooks Sync Failure (Broken sync damages trust).

High	
Run extensive automated integration tests and set up real-time sync failure alerts.

If Intuit introduces breaking changes to their API, build a backup sync option for Xero.

Founder Burnout (Technical issues delay launch).

High	
Commit to a strict 25-hour weekly development schedule and delegate administrative work.

If the MVP is not 70% complete by Oct 31, 2026, delay the soft launch to Q2 2027.

High Customer Churn (Acquisition is lost).

High	
Focus on first-day usability and use analytics to track active feature usage.

If monthly churn exceeds 5% for two consecutive months, conduct 20 user exit interviews.

  


BSP_Market_Research_Report_2026.docx


BSP_Business_Plan_2026.docx