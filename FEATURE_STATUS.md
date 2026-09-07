# Feature status — Property, leasing & facilities

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 516 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 1 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 3 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 6 | 0 | Native records/view |
| Reports & analytics | report | 15 | 0 | Native records/view |
| Activity & audit trail | audit | 12 | 0 | Native records/view |
| Provider connections | integration | 4 | 0 | Provider request records only |
| Lease & Amendment Ingestion | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| CAM Clause Abstraction | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Effective-Dated Lease Rules | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Landlord Statement Ingestion | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Property & Occupancy Registry | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Pro-Rata Share Validation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Expense Eligibility Classification | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Contractual Exclusion Testing | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Capital-Expense Treatment | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Controllable-Expense Cap | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Base-Year & Expense-Stop Reconciliation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Gross-Up & Occupancy Validation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Administrative & Management Fee Validation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Tax & Insurance Pass-Through Review | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Duplicate & Misallocated Charge Detection | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Landlord Evidence Requests | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Audit-Rights & Deadline Calendar | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Tenant Claim Package | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Landlord Response & Negotiation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Recovery Ledger & Portfolio Analytics | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Vendor contract library | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Location asset registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Work order ingestion | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Priority classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Response time calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resolution time calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Uptime calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Preventive maintenance compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Repeat failure detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exclusion validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SLA credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor claim package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Location vendor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property asset registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Arrival completion tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Preventive maintenance validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Labor rate audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material rate audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trip emergency fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate work-order billing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SLA response monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manager approval | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property vendor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property transaction registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Closing statement ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross commission calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Co-broker split validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agent split calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Team referral allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Franchise desk fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cap threshold monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lease renewal commission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contingent payment tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Closing cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agent dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commission statements | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Office agent profitability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lease amendment library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Allowance definition extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Premises project registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget draw schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligible cost classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contractor invoice evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lien waiver collection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Completion milestone tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Landlord approval conditions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Submission deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draw package generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Information request workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reimbursement tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unused allowance forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio recovery analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Title & Curative | records | 1 | 0 | Native records/view |
| Fraud Control | records | 1 | 0 | Native records/view |
| Disbursement | records | 1 | 0 | Native records/view |
| Closing Files | records | 1 | 0 | Native records/view |
| Closing File | records | 1 | 0 | Native records/view |
| Title Search | records | 1 | 0 | Native records/view |
| Lien Record | records | 1 | 0 | Native records/view |
| Curative Item | records | 1 | 0 | Native records/view |
| Payoff Statement | records | 1 | 0 | Native records/view |
| Wire Instruction | records | 1 | 0 | Native records/view |
| Fraud Alert | records | 1 | 0 | Native records/view |
| CD Reconciliation | records | 1 | 0 | Native records/view |
| Escrow Ledger | records | 1 | 0 | Native records/view |
| Disbursement Approval | records | 1 | 0 | Native records/view |
| Recording Package | records | 1 | 0 | Native records/view |
| Policy Issuance | records | 1 | 0 | Native records/view |
| Draft: Curative Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Wire Fraud Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Closing Summary Drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Acquisition Project | records | 1 | 0 | Native records/view |
| Acquisition Parcel | records | 1 | 0 | Native records/view |
| Ownership Interest | records | 1 | 0 | Native records/view |
| Parcel Appraisal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Easement Offer | records | 1 | 0 | Native records/view |
| Negotiation Event | records | 1 | 0 | Native records/view |
| Acquisition Agreement | records | 1 | 0 | Native records/view |
| Recording Receipt | records | 1 | 0 | Native records/view |
| Compensation Payment | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Deed interest extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appraisal comparison brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Negotiation preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agreement clause gap review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recording packet checklist | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Acquisition progress narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lease Abstraction | records | 1 | 0 | Native records/view |
| Rent Escalation Modeling | records | 1 | 0 | Native records/view |
| Renewal Negotiations | records | 1 | 0 | Native records/view |
| Portfolio Optimization | records | 1 | 0 | Native records/view |
| Market Comp Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Financial Calculators | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lease Comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Lab | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Alerts & iCal | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Audit Trail | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Run | records | 1 | 0 | Native records/view |
| Co tenancy clause watch | records | 1 | 0 | Native records/view |
| Membership Plans | records | 1 | 0 | Native records/view |
| Desk Management | records | 1 | 0 | Native records/view |
| Meeting Rooms | records | 1 | 0 | Native records/view |
| Room Bookings | records | 1 | 0 | Native records/view |
| Phone Booths | records | 1 | 0 | Native records/view |
| Booth Bookings | records | 1 | 0 | Native records/view |
| Check-in Tracking | records | 1 | 0 | Native records/view |
| Visitor Management | records | 2 | 0 | Native records/view |
| Member Directory | records | 1 | 0 | Native records/view |
| Maintenance Requests | records | 3 | 0 | Native records/view |
| Day Pass Management | records | 1 | 0 | Native records/view |
| Team Accounts | records | 2 | 0 | Native records/view |
| Parking Allocation | records | 1 | 0 | Native records/view |
| Storage Lockers | records | 1 | 0 | Native records/view |
| Mail & Packages | records | 1 | 0 | Native records/view |
| Amenity Management | records | 3 | 0 | Native records/view |
| Access Control | records | 2 | 0 | Native records/view |
| Community Board | records | 2 | 0 | Native records/view |
| Referral Program | records | 1 | 0 | Native records/view |
| Usage Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cleaning Schedules | records | 1 | 0 | Native records/view |
| Guest WiFi | records | 1 | 0 | Native records/view |
| AI Member Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Room Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Newsletter Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Pricing Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Event Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Space Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Custom Tools (7 new) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI New Tools (Maintenance & Cleaning) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smart Desk Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reputation Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conflict Resolution | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility Health | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mentorship Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resource Marketplace | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cleaning Schedule Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parking Utilization Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage Allocation Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Phone Booth Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Memberships | records | 1 | 0 | Native records/view |
| Meeting bookings | records | 1 | 0 | Native records/view |
| Members | records | 1 | 0 | Native records/view |
| Maintenance | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Parking | records | 4 | 0 | Native records/view |
| Storage | records | 1 | 0 | Native records/view |
| Cleaning | records | 1 | 0 | Native records/view |
| Pricing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive maintenance occupancy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic pricing revenue optimization | records | 1 | 0 | Native records/view |
| Community growth viral loops | records | 1 | 0 | Native records/view |
| Amenity utilization prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member lifetime value modeling | records | 1 | 0 | Native records/view |
| Maintenance cleaning parking storage phonebooths lack ai end | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accesscontrol checkins lack ai anomaly detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limited guest wifi bandwidth management | records | 1 | 0 | Native records/view |
| Limited calendar integration no full google outlook adapter | integration | 1 | 0 | Provider request records only |
| Limited payment integration only stripe stub | integration | 1 | 0 | Provider request records only |
| No member mobile app for check in booking community | records | 1 | 0 | Native records/view |
| No webhooks | integration | 1 | 0 | Provider request records only |
| Residents | records | 2 | 0 | Native records/view |
| Properties | records | 4 | 0 | Native records/view |
| Finances | records | 2 | 0 | Native records/view |
| Violations | records | 4 | 0 | Native records/view |
| Meetings | records | 2 | 0 | Native records/view |
| Vendors | records | 3 | 0 | Native records/view |
| Architectural | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Emergency | records | 2 | 0 | Native records/view |
| Violation Enforcement Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reserve Study Projector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parking Assignment Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Architectural Compliance Scanner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Community Engagement Scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive HOA Problem Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assessment Fairness Audit (Pass 5) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI HOA Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Policy Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Conflict Resolution | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Legal Compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Event Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Sustainability Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Board Decision Helper | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Governance | records | 1 | 0 | Native records/view |
| Covenant variance precedent | records | 1 | 0 | Native records/view |
| agentic community manager handling routi | records | 1 | 0 | Native records/view |
| architectural compliance scanner flaggin | records | 1 | 0 | Native records/view |
| predictive community conflict forecastin | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| reserve study long term capital planner | records | 1 | 0 | Native records/view |
| parking and amenity assignment optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| community engagement retention scoring w | records | 1 | 0 | Native records/view |
| violation enforcement severity adviso | records | 1 | 0 | Native records/view |
| reserve study projector for capital | records | 1 | 0 | Native records/view |
| property assessment fairness audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| payment processing integration | integration | 1 | 0 | Provider request records only |
| homeowner self service portal beyond | records | 1 | 0 | Native records/view |
| webhook surface | integration | 2 | 0 | Provider request records only |
| file upload pipeline for architectura | records | 1 | 0 | Native records/view |
| real time meeting streaming | records | 1 | 0 | Native records/view |
| Rooms | records | 1 | 0 | Native records/view |
| Staging projects | records | 1 | 0 | Native records/view |
| Furniture | records | 1 | 0 | Native records/view |
| Appointments | records | 1 | 0 | Native records/view |
| Color palettes | records | 1 | 0 | Native records/view |
| Design styles | integration | 1 | 0 | Provider request records only |
| Before after | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Market analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Checklists | records | 1 | 0 | Native records/view |
| Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Listings | records | 1 | 0 | Native records/view |
| Property analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Room optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staging suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Furniture placement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Curb appeal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Style recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Color palette | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lighting design | integration | 1 | 0 | Provider request records only |
| Furniture recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seasonal staging | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trend forecaster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client proposal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appointment planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pricing calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Roi calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Listing generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social media | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Photo staging | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Open house optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Budget estimator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Valuation impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Neighborhood strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Checklist generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Decluttering guide | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renovation advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Virtual staging | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Competitor analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Buyer persona targeting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Furniture planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Listing copy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Roi simulator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic staging orchestration generating | records | 1 | 0 | Native records/view |
| 3d virtual staging with ar export | records | 1 | 0 | Native records/view |
| mls integration with comp based stagingp | integration | 1 | 0 | Provider request records only |
| buyer persona psychology modeling per ne | records | 1 | 0 | Native records/view |
| time to sale prediction tied to | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agent commission optimizer with performa | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| competitor mls comp analysis endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| buyer persona targeting endpoint | records | 1 | 0 | Native records/view |
| automated photo enhancement pipeline | records | 1 | 0 | Native records/view |
| vendorcontractor marketplace | records | 1 | 0 | Native records/view |
| project portfolio case studies | records | 1 | 0 | Native records/view |
| beforeafter photo gallery | records | 1 | 0 | Native records/view |
| payment invoicing integration | integration | 1 | 0 | Provider request records only |
| agent company white label | records | 1 | 0 | Native records/view |
| notifications 0 references | records | 1 | 0 | Native records/view |
| audit log 0 references | records | 1 | 0 | Native records/view |
| file upload module | records | 1 | 0 | Native records/view |
| mls integration | integration | 1 | 0 | Provider request records only |
| Building Portfolio | records | 1 | 0 | Native records/view |
| Energy Audits | records | 1 | 0 | Native records/view |
| Capacity Detection | records | 1 | 0 | Native records/view |
| Community Needs | records | 1 | 0 | Native records/view |
| Energy Aggregation | records | 1 | 0 | Native records/view |
| Grid Stability | records | 1 | 0 | Native records/view |
| Equity Scoring | records | 1 | 0 | Native records/view |
| Redistribution Plans | records | 1 | 0 | Native records/view |
| Demand Response | records | 1 | 0 | Native records/view |
| AI Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Impact Reports | records | 1 | 0 | Native records/view |
| Energy Savings | records | 1 | 0 | Native records/view |
| Alert Management | records | 1 | 0 | Native records/view |
| Compliance & Reporting | records | 1 | 0 | Native records/view |
| Partner Network | records | 1 | 0 | Native records/view |
| Utilization Opportunity Finder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pricing Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cohort Demand Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Real-Estate Arbitrage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tenant revenue share simulator | records | 1 | 0 | Native records/view |
| agentic utilization scout continuously s | records | 1 | 0 | Native records/view |
| demand forecasting dynamic pricing for s | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| community impact modeling quantifying jo | records | 1 | 0 | Native records/view |
| real estate arbitrage advisor recommendi | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| demand response monetization automating | records | 1 | 0 | Native records/view |
| equity driven redistribution recommendin | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| utilization opportunity finder endpoi | records | 1 | 0 | Native records/view |
| demand forecast ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| pricing recommender for underutilized | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| partner matching ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| equity analysis ai synthesizing commu | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited landlordtenant communication no | records | 1 | 0 | Native records/view |
| file upload for compliance documentat | records | 1 | 0 | Native records/view |
| webhook surface for utility meter | integration | 1 | 0 | Provider request records only |
| real time grid stability streaming | records | 1 | 0 | Native records/view |
| public marketplace for sharing offere | records | 1 | 0 | Native records/view |
| Facilities | records | 1 | 0 | Native records/view |
| Occupancy Prediction | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| License Plates | records | 2 | 0 | Native records/view |
| Revenue | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Mobile Payments | records | 1 | 0 | Native records/view |
| IoT Sensors | records | 1 | 0 | Native records/view |
| EV Charging | records | 1 | 0 | Native records/view |
| Reservations | records | 1 | 0 | Native records/view |
| Permits | records | 1 | 0 | Native records/view |
| Security Cameras | records | 4 | 0 | Native records/view |
| Feedback | records | 2 | 0 | Native records/view |
| Parking Zones | records | 1 | 0 | Native records/view |
| User Management | records | 1 | 0 | Native records/view |
| Data Export | records | 1 | 0 | Native records/view |
| AI History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Predictive | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Autonomous pricing engine | records | 1 | 0 | Native records/view |
| Computer vision enforcement | records | 1 | 0 | Native records/view |
| EV charging optimization | records | 1 | 0 | Native records/view |
| Resident permit fraud detection | records | 1 | 0 | Native records/view |
| Traffic-aware guidance | records | 1 | 0 | Native records/view |
| Maintenance without `/asset | records | 1 | 0 | Native records/view |
| Facilities without `/facility | records | 1 | 0 | Native records/view |
| Security without `/intrusion | records | 1 | 0 | Native records/view |
| No integrations with ride | integration | 1 | 0 | Provider request records only |
| No native mobile app (web only | records | 1 | 0 | Native records/view |
| Limited customer self | records | 1 | 0 | Native records/view |
| No integration with traffic/navigation apps (Waze, Google Maps for supply signaling) | integration | 1 | 0 | Provider request records only |
| No license plate database integration (DMV / vehicle registration) | integration | 1 | 0 | Provider request records only |
| No webhooks for external systems | integration | 1 | 0 | Provider request records only |
| Limited multi | records | 1 | 0 | Native records/view |
| Asset Lifecycle Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Intrusion Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auto Classify Permit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inspection Schedule Optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Code Interpretation Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Violation Severity Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Kanban | records | 1 | 0 | Native records/view |
| Jurisdiction rules | records | 1 | 0 | Native records/view |
| Fee calculator | records | 1 | 0 | Native records/view |
| ai plan pre screening | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| zoning assistant chatbot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| inspection routing optimization | records | 1 | 0 | Native records/view |
| violation escalation scoring | records | 1 | 0 | Native records/view |
| neighborhood impact analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| existing aihistory js and aipermit js stubs need r | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| plans without plan | records | 1 | 0 | Native records/view |
| inspections without inspection | records | 1 | 0 | Native records/view |
| violations without violation | records | 1 | 0 | Native records/view |
| code without code | records | 1 | 0 | Native records/view |
| cad gis integration plan viewer parcel maps | integration | 1 | 0 | Provider request records only |
| public portal online permit tracking doc submis | records | 1 | 0 | Native records/view |
| fee calculation engine | records | 1 | 0 | Native records/view |
| limited integration with title deed records integr | integration | 1 | 0 | Provider request records only |
| document versioning for plans | records | 1 | 0 | Native records/view |
| limited frontend only 7 pages for 19 | records | 1 | 0 | Native records/view |
| notifications layer grep shows only 1 mention | records | 1 | 0 | Native records/view |
| webhooks for inspection scheduling triggers | integration | 1 | 0 | Provider request records only |
| audit log only 1 audit reference | records | 1 | 0 | Native records/view |
| Property valuation agent work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage Units | records | 1 | 0 | Native records/view |
| Tenants | records | 2 | 0 | Native records/view |
| Climate Control | records | 2 | 0 | Native records/view |
| Access Logs | records | 2 | 0 | Native records/view |
| Insurance | records | 2 | 0 | Native records/view |
| Move In/Out | records | 2 | 0 | Native records/view |
| Promotions | records | 2 | 0 | Native records/view |
| Waitlist | records | 1 | 0 | Native records/view |
| dynamic pricing by unit typelocation | records | 1 | 0 | Native records/view |
| predictive maintenance scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| churn prevention program | records | 1 | 0 | Native records/view |
| occupancy forecasting promotions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| tenant portfolio segmentation | records | 1 | 0 | Native records/view |
| security event intelligence | records | 1 | 0 | Native records/view |
| unitsizingrecommendation rightsize sugges | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| churnprediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| latepaymentrisk collections triage | records | 1 | 0 | Native records/view |
| securityalertanalysis cameraalarm summari | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| demand forecasting ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| tenant portal selfservice | records | 1 | 0 | Native records/view |
| online reservationpayment workflow | records | 1 | 0 | Native records/view |
| autorenewal lease management | records | 1 | 0 | Native records/view |
| late fee automation | records | 1 | 0 | Native records/view |
| auction management for abandoned units | records | 1 | 0 | Native records/view |
| payment gateway integration | integration | 1 | 0 | Provider request records only |
| public webhook system | integration | 1 | 0 | Provider request records only |
| Hvac | records | 1 | 0 | Native records/view |
| Lighting | records | 1 | 0 | Native records/view |
| Energy | records | 1 | 0 | Native records/view |
| Comfort | records | 1 | 0 | Native records/view |
| Space | records | 1 | 0 | Native records/view |
| Water | records | 1 | 0 | Native records/view |
| Waste | records | 1 | 0 | Native records/view |
| Fire | records | 1 | 0 | Native records/view |
| Elevators | records | 1 | 0 | Native records/view |
| Building health | records | 1 | 0 | Native records/view |
| Threshold alerts | records | 1 | 0 | Native records/view |
| Maintenance prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Occupancy optimization | records | 1 | 0 | Native records/view |
| Predictive maintenance ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security anomaly | records | 1 | 0 | Native records/view |
| Energy forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comfort optimization | records | 1 | 0 | Native records/view |
| Water usage optimization | records | 1 | 0 | Native records/view |
| Chilled water load shed | records | 1 | 0 | Native records/view |
| wholebuilding energy optimization | records | 1 | 0 | Native records/view |
| thermal comfort prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive maintenance engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| anomaly detection for security | records | 1 | 0 | Native records/view |
| occupancydriven demand response | records | 1 | 0 | Native records/view |
| water waste optimization | records | 1 | 0 | Native records/view |
| occupancyoptimization hvaclighting autotu | records | 1 | 0 | Native records/view |
| predictivemaintenance failure prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| energyforecast ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| comfortoptimization energy vs comfort | records | 1 | 0 | Native records/view |
| securityanomalydetection | records | 1 | 0 | Native records/view |
| waterusageoptimization leak detection | records | 1 | 0 | Native records/view |
| realtime building dashboard route stubs o | records | 1 | 0 | Native records/view |
| iot device protocol integration bacnet mo | integration | 1 | 0 | Provider request records only |
| occupant mobile app endpoints | records | 1 | 0 | Native records/view |
| tenant submetering billback | records | 1 | 0 | Native records/view |
| limited emergency response workflows | records | 1 | 0 | Native records/view |
| vendor management contractors | records | 1 | 0 | Native records/view |
| demandresponse grid integration | integration | 1 | 0 | Provider request records only |
| Leads | records | 1 | 0 | Native records/view |
| Transactions | records | 1 | 0 | Native records/view |
| Showings | records | 1 | 0 | Native records/view |
| Campaigns | records | 1 | 0 | Native records/view |
| Open Houses | records | 1 | 0 | Native records/view |
| Social Posts | records | 1 | 0 | Native records/view |
| Flyers | records | 1 | 0 | Native records/view |
| Agents | records | 1 | 0 | Native records/view |
| Market Reports | records | 1 | 0 | Native records/view |
| Performance | records | 1 | 0 | Native records/view |
| Commissions | records | 1 | 0 | Native records/view |
| Dashboard | records | 1 | 0 | Native records/view |
| Search | records | 1 | 0 | Native records/view |
| Favorites | records | 2 | 0 | Native records/view |
| Saved Searches | records | 2 | 0 | Native records/view |
| Lead Qualifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Listing Description | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Price Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Email Sequence Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social Post Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Neighborhood Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Offer Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investment Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Buyer Persona Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Virtual Tour Creator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rental Price Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tenant Screener | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mortgage Calculator Pro | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investment Property Finder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Real Estate Appraiser | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Showing Scheduler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Open House Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comparable Market Analysis (CMA) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Checker | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Lead Scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Buyer Journey Personalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pipeline Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| comp analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| esign workflow | integration | 1 | 0 | Provider request records only |
| dual agency check | records | 1 | 0 | Native records/view |
| closing workflow | records | 1 | 0 | Native records/view |
| crm sync | records | 1 | 0 | Native records/view |
| mobile agent app | records | 1 | 0 | Native records/view |
| commission forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| rental management | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 516 feature pages were visited in the browser; 514 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 252 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

252 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
