# Home Self-Hosting Solution Business Plan

## Executive Summary

### Business Concept
A service-based business providing turnkey self-hosting solutions for home users, utilizing refurbished Lenovo ThinkCentre M710q small form factor PCs with pre-configured software stacks. The service targets non-technical homeowners and renters seeking alternatives to cloud subscriptions, offering one-time installation with optional ongoing support.

### Value Proposition
- **Privacy Control**: Data remains in customer's home
- **Cost Savings**: Eliminates recurring cloud subscription fees
- **Simplicity**: Grandma-friendly interface with professional installation
- **Reliability**: Enterprise-grade hardware with stable, well-maintained software
- **Flexibility**: Standardized base with unlimited customization potential

### Growth Strategy
Phase 1 MVP launches hyperlocally (single city block), validating unit economics and processes before scaling to citywide, then multi-city operations through local representatives.

## Market Analysis

### Target Market
**Primary**: Homeowners and renters aged 25-65 with:
- Multiple cloud subscriptions (Netflix, Spotify, Google Drive, etc.)
- Privacy concerns about data collection
- Desire for simplified technology solutions
- Household income $50,000+
- Basic internet connectivity (50+ Mbps)
- Subscription fatigue and cost consciousness

### Market Pain Points
- Rising costs of multiple cloud services
- Privacy concerns with big tech data collection  
- Complexity of existing self-hosting solutions
- Fear of technology complexity and maintenance
- Desire for digital independence without technical expertise

### Competitive Landscape
**Direct competitors**: Synology, QNAP (complex, still require technical knowledge)
**Indirect competitors**: Cloud services (convenient but expensive long-term)
**Advantage**: Full-service installation and grandma-friendly operation

## Service Offerings

### Installation Packages

**Basic Package - $400**
- Lenovo ThinkCentre M710q (refurbished, upgraded)
- 16GB RAM, 500GB SSD, 2TB backup drive
- Pre-configured software stack
- 1.5-hour installation and training
- Digital manual access
- 30-day email support

**Add-ons:**
- More RAM (32GB total): $50
- More Storage (1TB SSD + 4TB backup): $75
- Extended Support (90-day phone/email + follow-up visit): $100
- Wireless Keyboard/Trackpad (Logitech K400 Plus): $40
- 7" Touchscreen Display with mounting options: $100
- Power Protection (UPS with clean shutdown): $100
- Off-site Backup Storage: $10-25/month
- Printed Manual: $30

**Bundle Options:**
- Complete Setup Kit (Keyboard + Display + Power Protection): $200 (save $40)
- Power User Kit (More RAM + More Storage + Extended Support): $200 (save $25)
- Everything Bundle (All upgrades + Complete Setup Kit): $475 (save $90)

**Add-ons:**
- Printed manual: $30

### Software Stack (Standardized)

- See `software_list.md`.

## Customer Support Framework

### Tier 1: Self-Service
- Comprehensive online manual with video tutorials
- Community forum for user discussions
- FAQ covering 80% of common issues
- Simple troubleshooting flowcharts

### Tier 2: Filtered Support Form
Web-based form categorizing issues:
- **Hardware Issues**: Device won't start, connectivity problems
- **Software Issues**: Services not working, interface problems  
- **Network Issues**: Redirect to ISP or router manufacturer
- **User Questions**: Direct to manual sections or forum

### Tier 3: Ticket System
For validated service-related issues:
- 48-hour email response guarantee
- Remote diagnostic access (with customer permission)
- Escalation procedures for complex problems

### Tier 4: Phone Support  
Direct line for Advanced Package customers:
- Business hours only (9 AM - 6 PM local time)
- 15-minute maximum per call
- Hardware replacement coordination

## MVP Launch Strategy

### Geographic Scope: Single City Block
**Rationale**: 
- Walking distance for installations and support
- Concentrated word-of-mouth marketing
- Minimal travel costs
- Personal accountability builds reputation

### Launch Process:
1. **Customer Acquisition**: Door-to-door introduction, local social media
2. **Initial Installations**: 5-10 customers for validation
3. **Process Refinement**: Document lessons learned, optimize procedures
4. **Success Metrics Validation**: Confirm unit economics and satisfaction
5. **Expansion Decision**: Scale to city or pivot based on data

### Success Metrics:
- Customer acquisition cost < $25
- Installation completion time < 1.5 hours average
- Customer satisfaction score > 4.5/5
- Support call frequency < 2 per customer per month
- Positive unit economics with 40%+ gross margin

## Technical Architecture

### Hardware Specifications
**Lenovo ThinkCentre M710q** (eBay sourcing):
- Intel i5-6500T or better
- Upgraded to 16GB+ RAM
- Primary SSD (500GB-1TB)
- Backup drive (2TB-4TB external USB)
- Gigabit Ethernet required
- Estimated hardware cost: $150-200 per unit (refurbished/bulk)

### Software Selection Criteria:
- **Mature projects** with 3+ years active development
- **Large user base** (10,000+ installations)
- **Docker compatibility** for easy deployment
- **Web-based interfaces** for user accessibility
- **Declarative configuration** for NixOS integration
- **Strong backup/restore** capabilities

### Remote Management:
- SSH access for system administration
- Automated monitoring and alerting
- Remote backup verification
- NixOS generation rollback capability

## Financial Projections

### MVP Phase (10 customers, 3 months)
**Revenue**: 
- 6 Basic packages: $2,400
- 4 Advanced packages: $2,796  
- 2 Printed manuals: $60
- **Total**: $5,256

**Costs**:
- Hardware (10 units @ $175): $1,750
- Labor (15 hours @ $25): $375
- Materials and tools: $200
- **Total**: $2,325

**Net Profit**: $2,931 (56% margin)

### Scaling Projections (Year 1)
- Month 1-3: MVP (10 customers)
- Month 4-6: City expansion (30 customers)
- Month 7-12: Multi-neighborhood (100 customers)

**Annual Projections**:
- Revenue: $65,800
- COGS: $27,500
- Operating Expenses: $18,000  
- **Net Income**: $20,300

## Scaling Framework

### Phase 2: Citywide Expansion
- Hire first technician/installer
- Develop standardized training program
- Implement customer relationship management system
- Establish parts inventory and logistics

### Phase 3: Multi-City Operations  
- Recruit local representatives (employment model TBD)
- Standardize all operational procedures
- Implement quality assurance protocols
- Develop franchise/contractor/employee framework

### Decision Points for Scaling:
- **50+ satisfied customers** in MVP area
- **Consistent 45%+ gross margins**
- **<2 support calls per customer monthly**
- **4.5+ customer satisfaction scores**
- **Validated referral rates** >25%

## Risk Assessment

### Technical Risks:
- **Hardware sourcing quality**: Mitigate with standardized testing procedures and seller relationships
- **Hardware failure rates**: Build parts inventory and replacement procedures
- **Software stability**: Use only mature, well-tested applications
- **Customer network issues**: Clear scope limitations and referral procedures

### Business Risks:
- **Market demand uncertainty**: MVP validates before major investment
- **Support burden**: Tiered system and clear boundaries prevent overflow
- **Competition from big tech**: Focus on privacy and control differentiators
- **Scaling complexity**: Phased approach with clear success metrics

### Mitigation Strategies:
- Conservative cash management during MVP
- Comprehensive customer agreements limiting scope
- Insurance coverage for equipment and liability
- Regular backup of all customer configurations
- Clear escalation procedures for complex issues

## Legal Considerations

### Service Agreements:
- Clear scope of services and limitations
- Data privacy and security responsibilities
- Hardware warranty terms and replacement
- Customer obligations (network requirements, access)

### Liability Management:
- Professional liability insurance
- Equipment replacement guarantees
- Data loss limitation clauses
- Network/internet dependency disclaimers

### Intellectual Property:
- Open source software compliance
- Customer data ownership clarity
- Service methodology documentation

## Success Metrics and KPIs

### MVP Phase Metrics:
- Installation completion rate: >95%
- Average installation time: <1.5 hours
- Customer satisfaction: >4.5/5
- Support call frequency: <2 per customer/month
- Hardware failure rate: <5%
- Customer referral rate: >25%

### Financial KPIs:
- Gross margin: >45%
- Customer acquisition cost: <$25
- Customer lifetime value: >$400
- Support cost per customer: <$30/year

### Operational KPIs:
- Response time for support tickets: <48 hours
- First-call resolution rate: >70%
- Installation rescheduling rate: <10%

## Next Steps

### Immediate Actions (Month 1):
1. Finalize software stack and test installation procedures
2. Source initial inventory of M710q units from eBay
3. Develop customer agreements and service documentation
4. Create basic website with subscription cost calculator
5. Identify MVP neighborhood and begin customer outreach

### Short-term Goals (Months 2-3):
1. Complete 5-10 MVP installations
2. Gather customer feedback and iterate processes
3. Document all procedures for future training
4. Validate financial model and unit economics
5. Plan expansion strategy based on results

### Decision Points:
- **Month 3**: Evaluate MVP success and decide on citywide expansion
- **Month 6**: Assess single-operator capacity and hiring needs  
- **Month 12**: Determine multi-city expansion model and structure

---

*This business plan serves as a living document to be updated based on market feedback and operational experience during the MVP phase.*
