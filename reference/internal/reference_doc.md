# Self-Hosting Service Reference Document

## Business Overview

**Service**: Turnkey self-hosting solutions for home users using refurbished enterprise hardware with pre-configured software stacks.

**Target Market**: Homeowners and renters aged 25-65 with multiple subscriptions, privacy concerns, and desire for simplified technology solutions.

**Value Proposition**: One-time fee eliminates recurring cloud costs while maintaining data privacy and control.

## Service Offerings & Pricing

### Packages

**Basic Package - $400**
- Lenovo ThinkCentre M710q (refurbished)
- 16GB RAM, 500GB SSD, 2TB backup drive
- Pre-configured software stack
- 1.5-hour installation and training
- Digital manual access
- 30-day email support

**Add-ons**
- More RAM (32GB total): $50
- More Storage (1TB SSD + 4TB backup): $75
- Extended Support (90-day phone/email + follow-up visit): $100
- Wireless Keyboard/Trackpad (Logitech K400 Plus): $40
- 7" Touchscreen Display with mounting options: $100
  - Desktop stand (included)
  - Wall mount (flush VESA): +$25
  - Under-cabinet mount: +$35
  - Articulating arm: +$45
- Power Protection (UPS with clean shutdown): $100
- Off-site Backup Storage: $10-25/month (third-party partnership)
- Printed Manual: $30

**Bundle Options**
- Complete Setup Kit (Keyboard + Display + Power Protection): $200 (save $40)
- Power User Kit (More RAM + More Storage + Extended Support): $200 (save $25)
- Everything Bundle (All hardware upgrades + Complete Setup Kit): $475 (save $90)

### Unit Economics
- Hardware cost: ~$175 per unit (base configuration)
- RAM upgrade cost: ~$35 (16GB additional)
- Storage upgrade cost: ~$60 (500GB SSD + 2TB drive difference)
- Labor: 1.5 hours @ $25/hour = $37.50
- Professional cable management: Included all tiers
- **Basic package margin**: ~46%
- **Add-on margins**: 30-60% (reduced for value positioning)
- **Target gross margin**: 40%+

## Hardware Specifications

### Primary Hardware: Lenovo ThinkCentre M710q

**Sourcing**: eBay, bulk purchases from enterprise refresh
**Target specs**:
- Intel i5-6500T or better
- Upgraded to 16GB+ DDR4 RAM
- 500GB-1TB SSD (primary)
- 2TB-4TB external USB drive (backup)
- Gigabit Ethernet (required)
- All USB ports functional
- Clean Windows license (for resale compliance)

**Quality checklist**:
- Boot test and memory check
- All ports functional
- Clean exterior/interior
- BIOS accessible and configurable
- Network connectivity verified
- No missing components

### Cost targets
- Hardware acquisition: $120-150
- Upgrades (RAM/SSD): $25-50
- **Total hardware cost**: $150-200

## Software Stack (Standardized)

### Base System
- **OS**: NixOS (stable channel)
- **Container platform**: Docker + Docker Compose
- **Management interface**: Portainer Community Edition
- **Remote access**: Tailscale mesh networking
- **Backup system**: Automated daily backups to external drive

### Core Applications
1. **Nextcloud** - File sync, calendar, contacts
2. **Jellyfin** - Media streaming server
3. **Pi-hole** - Network-wide ad blocking and DNS
4. **Home Assistant** - Smart home automation hub
5. **Vaultwarden** - Password manager (Bitwarden compatible)
6. **Immich** - Photo management and backup

### Optional Applications (One-click install)
- Plex Media Server
- Paperless-ngx (document management)
- Wireguard VPN server
- Gitea (personal Git hosting)
- Monitoring stack (Grafana/Prometheus)
- Frigate (security camera NVR)

### Software Selection Criteria
- **Mature projects**: 3+ years active development
- **Large user base**: 10,000+ active installations
- **Docker support**: Official or well-maintained images
- **Web interfaces**: No command-line user interaction
- **Declarative configuration**: Works well with NixOS
- **Strong backup/restore**: Critical for reliability

## Installation Procedures

### Pre-installation Checklist
- [ ] Customer network requirements confirmed (50+ Mbps, Ethernet port)
- [ ] Hardware tested and configured
- [ ] Software stack pre-installed and tested
- [ ] Customer expectations set (scope, limitations)
- [ ] Installation appointment scheduled

### Installation Process (1.5 hours target)
1. **Setup** (15 min)
   - Connect hardware to network and power
   - Verify network connectivity
   - Access web interface from customer device

2. **Configuration** (30 min)
   - Set up user accounts and passwords
   - Configure basic services (Nextcloud, Jellyfin)
   - Set up backup schedules
   - Test remote access (if applicable)

3. **Training** (30 min)
   - Walk through web dashboard
   - Demonstrate core applications
   - Cover basic troubleshooting
   - Provide contact information and manual access

4. **Documentation** (15 min)
   - Record configuration details
   - Customer sign-off on installation
   - Schedule follow-up if Advanced package

### Post-installation
- Send digital manual link within 24 hours
- Add to monitoring/support system
- Schedule any follow-up visits

## Customer Support Framework

### Tier 1: Self-Service
- **Online manual**: Comprehensive guides with screenshots
- **Video tutorials**: Basic operations and troubleshooting
- **Community forum**: User discussions and peer support
- **FAQ section**: Covers 80% of common issues

### Tier 2: Support Form (Filtering)
**Hardware issues** → Ticket system
- Device won't power on
- Network connectivity problems
- Hardware replacement needs

**Software issues** → Ticket system
- Applications not working
- Interface problems
- Backup/restore issues

**Network issues** → Redirect to ISP/router support
**User questions** → Direct to manual/forum

### Tier 3: Ticket System
- 48-hour response guarantee
- Remote diagnostic access (with permission)
- Hardware replacement coordination
- Escalation to phone support if needed

### Tier 4: Phone Support
- Advanced package customers only
- Business hours: 9 AM - 6 PM local time
- 15-minute maximum per call
- Focus on urgent hardware/connectivity issues

## Quality Standards

### Installation Standards
- All services accessible via web interface
- Backup system tested and verified
- User accounts properly configured
- Documentation completed
- Customer can access primary functions independently

### Support Standards
- Ticket response: <48 hours
- Phone answer: <3 rings during business hours
- First-call resolution: >70%
- Customer satisfaction: >4.5/5

### Hardware Standards
- <5% failure rate in first year
- All components tested before installation
- Clean, professional appearance
- Proper cable management

## Success Metrics & KPIs

### Operational Metrics
- Installation time: <1.5 hours average
- Installation completion rate: >95%
- Support tickets per customer: <2/month
- Hardware failure rate: <5%
- Customer referral rate: >25%

### Financial Metrics
- Gross margin: >45%
- Customer acquisition cost: <$25
- Customer lifetime value: >$400 (plus recurring backup revenue)
- Support cost per customer: <$30/year
- Monthly recurring revenue target: 30% of customer base

### Customer Satisfaction
- Installation satisfaction: >4.5/5
- Overall service rating: >4.5/5
- Would recommend to others: >90%

## Legal & Safety Considerations

### Service Agreements
- Clear scope definition and limitations
- Hardware warranty terms (30-90 days)
- Data privacy and ownership clauses
- Network dependency disclaimers
- Support boundaries and escalation

### Liability Protection
- Professional liability insurance required
- Equipment replacement procedures
- Data loss limitation clauses
- Clear documentation of customer responsibilities

### Compliance
- Open source license compliance
- Customer data privacy (no access without permission)
- Local business licensing requirements
- Equipment disposal (e-waste) procedures

## Growth & Scaling

### MVP Success Criteria
- 10+ satisfied customers in local area
- Consistent 45%+ gross margins
- <2 support calls per customer monthly
- 4.5+ customer satisfaction scores
- 25%+ referral rate

### Scaling Decision Points
- **Month 3**: Evaluate MVP results, decide on citywide expansion
- **Month 6**: Assess capacity, consider hiring
- **Month 12**: Multi-city expansion model decision

### City Agent Requirements (Future)
- Technical aptitude for installations
- Customer service skills
- Local market knowledge
- Vehicle for transportation
- Insurance and bonding

## Resources & Contacts

### Key Suppliers
- **Hardware**: eBay power sellers (maintain 3+ sources)
- **Storage**: Amazon/Newegg for drives
- **Components**: Local computer stores for emergency parts
- **Displays**: Thrift stores, surplus electronics, Chinese manufacturers
- **Backup Services**: Third-party partnerships (TBD - Wasabi, Backblaze B2, etc.)

### Software Resources
- **Documentation**: Each application's official docs
- **Community forums**: r/selfhosted, r/NixOS, HomeAssistant community
- **Updates**: NixOS stable channel, security mailing lists
- **Configuration management**: Git repository for all NixOS configurations

### Professional Services
- **Legal**: Business attorney for contracts
- **Insurance**: Professional liability coverage
- **Accounting**: Bookkeeping and tax preparation

## Emergency Procedures

### Hardware Failure
1. Diagnose remotely if possible
2. Coordinate replacement hardware
3. Restore from backup
4. Schedule on-site visit if needed
5. Document failure for pattern analysis

### Software Issues
1. Remote troubleshooting via Tailscale
2. Check logs and system status
3. Restart services or containers
4. Rollback to previous NixOS generation if needed
5. Restore from backup if necessary
6. Update documentation with solution

### Customer Emergency Contact
- Email: support@[domain]
- Phone: [number] (Advanced customers)
- After-hours: Emergency ticket system only

---

**Document Version**: 1.0  
**Last Updated**: [Date]  
**Next Review**: [Date + 3 months]
