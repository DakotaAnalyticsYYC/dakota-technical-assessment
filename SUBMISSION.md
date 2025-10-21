# Submission Guidelines

## Before Submitting

### 1. Complete the Implementation
- [ ] All six components implemented (API, ingestion, orchestration, database, dbt, reports)
- [ ] Documentation created in `/docs/` folder
- [ ] Makefile with required commands created
- [ ] Tests written and passing

### 2. Test in Clean Environment
```bash
# Remove everything and test from scratch
make clean
rm -rf venv/ .venv/ __pycache__/

# Test the full flow
make setup
make run
make test
make report
```

### 3. Verify Deliverables

Check your repository includes:
- [ ] `Makefile` with: setup, run, test, report, clean
- [ ] `docker-compose.yml` with all services
- [ ] `.env.example` with all required variables
- [ ] `docs/architecture.md` - your architecture and design
- [ ] `docs/decisions.md` - technical decisions and rationale
- [ ] `docs/er_diagram.png` - database schema diagram
- [ ] `README.md` - updated with your setup instructions
- [ ] All source code properly organized
- [ ] Tests included

### 4. Final Checks
- [ ] Repository is **public**
- [ ] No sensitive data committed (API keys, passwords, etc.)
- [ ] `.env` is in `.gitignore` (not committed)
- [ ] `make setup && make run` works from fresh clone

## How to Submit

Email to: **technical-assessment@dakotaanalytics.com**

**Subject:** Technical Assessment Submission - [Your Name]

**Body:**
```
Name: [Your Full Name]
GitHub Repository: [Your fork URL]
Orchestration Tool: [Tool you chose]

Brief Summary (2-3 sentences):
[Describe your approach and key decisions]

Time Spent: [Approximate hours]
```

## What We'll Do

1. Clone your repository
2. Review your documentation
3. Run `make setup && make run`
4. Examine generated reports
5. Review your code, tests, and architecture
6. Evaluate based on the criteria in README.md

## Timeline

- **Time to complete**: ~8-12 hours
- **Submission deadline**: 7 days from when you received the assessment
- **Response time**: We'll respond within 5 business days

## Questions?

For requirement clarifications only: **technical-assessment@dakotaanalytics.com**

Good luck!
