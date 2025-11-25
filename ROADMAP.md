# MYL Roadmap

**My Last [Whatever].zip** - Personal digital legacy management, built in public.

## Vision

MYL is a personal-first digital archive system that earns your trust incrementally:
- Start with **convenience** (CLI tools, quick access)
- Build to **security** (encrypted storage, legacy planning)
- Earn **trust** (health info, PII, digital will)

When you trust MYL with your health information, you know we've built something real.

---

## Development Phases

### Phase 0: Foundation (Current - Q1 2025)
**Goal**: Establish core CLI and prove the concept

- [x] Project structure and Python scaffold
- [x] Security-first architecture (no secrets in code)
- [x] MIT License and public repository
- [ ] GitHub account and repository setup
- [ ] OpenRouter AI integration (multi-model support)
- [ ] Windows Credential Manager integration
- [ ] Basic chat interface with AI

**Deliverable**: Working CLI that can chat with AI models securely

### Phase 1: Personal Archive (Q1 2025)
**Goal**: Encrypted personal journaling and note-taking

- [ ] Encrypted local storage (SQLite + GPG/age encryption)
- [ ] Journal command (`myl journal "Today I learned..."`)
- [ ] Memory recall (`myl memory search "health decisions"`)
- [ ] Tag and categorization system
- [ ] Full-text search across encrypted notes
- [ ] Export to plain markdown (decrypted)

**Deliverable**: HIPAA-safe personal journaling system

**Trust Level**: Personal thoughts, daily reflections

### Phase 2: Legacy Planning (Q2 2025)
**Goal**: Digital will and trusted access system

- [ ] Vault system for important credentials (encrypted references, not storage)
- [ ] Trusted contacts management
- [ ] Time-locked information release
- [ ] Emergency access protocols
- [ ] Dead man's switch implementation
- [ ] Legacy package creation (`myl package --for=family`)

**Deliverable**: System for managing post-mortem digital access

**Trust Level**: Important documents, access instructions

### Phase 3: Health Archive (Q2-Q3 2025)
**Goal**: HIPAA-compliant health information management

- [ ] Medical records storage (encrypted)
- [ ] Medication tracking
- [ ] Provider information management
- [ ] Health timeline visualization
- [ ] Export for medical emergencies
- [ ] Integration with health data APIs (Apple Health, etc.)

**Deliverable**: Secure health information archive

**Trust Level**: Medical history, prescriptions, diagnoses

### Phase 4: Identity Management (Q3 2025)
**Goal**: Portable digital identity with SSL/API key management

- [ ] SSL certificate generation and management
- [ ] API key storage and rotation
- [ ] Service credential vault
- [ ] MyL.zip platform integration
- [ ] Multi-device sync (encrypted)
- [ ] Audit log for all access

**Deliverable**: Complete identity management suite

**Trust Level**: Production credentials, business data

### Phase 5: Public Platform (Q4 2025)
**Goal**: Web interface for public-facing services

- [ ] MyL.zip web platform launch
- [ ] Public profile pages (opt-in)
- [ ] Shared archives (controlled disclosure)
- [ ] Community features
- [ ] Developer API
- [ ] Mobile companion app

**Deliverable**: Full platform ecosystem

**Trust Level**: Selective public sharing from private archive

---

## Technical Milestones

### v0.1.0 - CLI Foundation (January 2025)
- Python CLI with Typer
- OpenRouter integration
- Secure configuration management
- Basic commands working

### v0.2.0 - Personal Archive (February 2025)
- Encrypted journaling
- Memory system
- Search functionality
- Export capabilities

### v0.3.0 - Legacy Planning (March 2025)
- Vault system
- Trusted contacts
- Emergency access
- Time-locked releases

### v0.4.0 - Health Archive (April 2025)
- HIPAA-compliant storage
- Medical records management
- Health timeline
- Emergency exports

### v0.5.0 - Identity Management (May 2025)
- SSL certificate management
- API key vault
- MyL.zip platform integration
- Multi-device sync

### v1.0.0 - Public Launch (June 2025)
- Web platform live
- Mobile app released
- Community features
- Developer API available

---

## Success Metrics

**Phase 1 Success**: You use it for daily journaling
**Phase 2 Success**: You store important legacy documents
**Phase 3 Success**: You trust it with health information ✨
**Phase 4 Success**: You manage production credentials with it
**Phase 5 Success**: Others trust it with their data

---

## Open Questions

1. Should we support multiple encryption backends (GPG, age, platform-native)?
2. What's the right balance between local-only and optional cloud sync?
3. How do we handle the dead man's switch without requiring a server?
4. What health data formats should we prioritize?
5. Should the public platform be fully separate or same codebase?

---

## Contributing

This is built in public, but it's personal-first. See [CONTRIBUTING.md](CONTRIBUTING.md) for:
- Code style guidelines
- Security requirements
- Testing standards
- Documentation expectations

---

**Current Status**: Phase 0 - Foundation  
**Next Milestone**: v0.1.0 - CLI Foundation  
**Last Updated**: 2024-11-25
