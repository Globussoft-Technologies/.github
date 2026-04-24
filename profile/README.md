<div align="center">

<img src="https://github.com/Globussoft-Technologies.png" width="120" alt="Globussoft Technologies" />

# Globussoft Technologies

**Building intelligent software products that transform industries.**

[![Website](https://img.shields.io/badge/Website-globussoft.com-6f42c1?style=for-the-badge&logo=google-chrome&logoColor=white)](https://globussoft.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Globussoft-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/globussoft-technologies)
[![Twitter](https://img.shields.io/badge/Twitter-@Globussoft-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/globussoft)
[![Email](https://img.shields.io/badge/Email-hello@globussoft.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@globussoft.com)

</div>

---

## About Us

**Globussoft Technologies** is a product-first software company that designs, builds, and ships AI-powered SaaS products across CRM, healthcare, media, advertising analytics, and vertical ERP markets. We are a team of 500+ engineers, designers, and product thinkers across Bhilai and Bangalore who believe great software should be fast, intelligent, and beautiful.

We operate a portfolio of products, each solving a specific industry problem at scale, powered by modern tech stacks including TypeScript, React, Python, Kotlin, PHP, and more.

---

## Our Products

| Product | Description | Stack | Visibility |
|---------|-------------|-------|-----------|
| [**callified**](https://github.com/Globussoft-Technologies/callified) | Generative AI dialer for CRMs. AI robo-dials leads, qualifies them, and hands off to SDRs. Works with 100+ CRMs. | Python | Public |
| [**globussoft-crm**](https://github.com/Globussoft-Technologies/globussoft-crm) | Open-source CRM to track leads, manage contacts, and automate sales pipelines | JavaScript | Public |
| [**caratflow**](https://github.com/Globussoft-Technologies/caratflow) | Complete jewelry ERP platform covering inventory, manufacturing, retail POS, accounting, CRM, and e-commerce for jewelers worldwide | TypeScript / React | Public |
| [**globussoft-school-mis**](https://github.com/Globussoft-Technologies/globussoft-school-mis) | Open-source School Management System with 75+ modules, 11 user roles, LMS, Finance, HR, and admin portals | TypeScript | Public |
| [**medcore**](https://github.com/Globussoft-Technologies/medcore) | Modern healthcare platform | TypeScript | Public |
| [**voyagr**](https://github.com/Globussoft-Technologies/voyagr) | Travel experience platform | TypeScript | Public |
| **adsgpt** | Generative AI for ad creation and optimization | JavaScript | Private |
| **poweradspy** | AI-powered ad analytics and competitive intelligence tool | PHP | Private |
| **globusphone** | Mobile communication app | Kotlin | Private |
| **smashify** | Social / media engagement platform | JavaScript | Private |
| **videoraiq** | AI-driven video intelligence platform | JavaScript | Private |
| **socialX** | Social automation toolkit | C# | Private |

---

## Tech Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

</div>

---

## For New Developers — Getting Startedh

Welcome to Globussoft Technologies! Here is everything you need to hit the ground running.

### 1. Access and Accounts

- Request your **GitHub org membership** from your team lead or HR
- Enable **two-factor authentication (2FA)** on your GitHub account — it is required for all org members
- You will be added to the relevant **GitHub Team** that grants access to your project repositories
- Set up your local Git config: `git config --global user.email "you@globussoft.com"`

### 2. Repository Structure

Each product lives in its own repository under this organization. The naming convention is lowercase-kebab-case (e.g., `globussoft-crm`, `caratflow`). Public repos are licensed under **AGPL v3.0**; private repos are proprietary.

### 3. Branching Strategy

We follow **GitHub Flow**:

```
main                          <- production-ready, protected branch
feature/your-feature-name     <- all new work branches off main
fix/your-bug-fix-name         <- bug fixes
docs/update-something         <- documentation-only changes
```

Open a **Pull Request** against `main` when your work is ready for review.

### 4. Commit Message Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add AI lead scoring to callified
fix: resolve CRM contact deduplication bug
docs: update caratflow inventory module guide
refactor: clean up auth middleware
chore: upgrade Node.js dependencies
test: add unit tests for dialer service
```

### 5. Code Review Process

- Every PR requires **at least 1 approval** before merging
- Assign relevant teammates as reviewers — check the CODEOWNERS file if present
- Use **draft PRs** while work is still in progress
- Address all reviewer comments before merging
- CI/CD checks must pass before merge

### 6. Development Environment Setup

Every repository includes a `README.md` with project-specific setup. The general flow is:

```bash
# 1. Clone your repo
git clone https://github.com/Globussoft-Technologies/<repo-name>
cd <repo-name>

# 2. Set up environment variables
cp .env.example .env
# Edit .env with your local credentials (never commit this file)

# 3. Install dependencies
npm install               # JavaScript / TypeScript projects
pip install -r requirements.txt   # Python projects
composer install          # PHP projects

# 4. Run database migrations (if applicable)
npm run db:migrate

# 5. Start the development server
npm run dev
```

### 7. Issue Tracking

We manage all work through **GitHub Issues** within each repository. Key labels to know:

| Label | Meaning |
|-------|---------|
| `bug` | Something is broken |
| `feature` | New capability request |
| `enhancement` | Improvement to existing feature |
| `priority:high` | Needs immediate attention |
| `good first issue` | Great for new contributors |

Check your project's issues tab for tasks assigned to you. If you are unsure what to work on first, ask your team lead.

### 8. CI / CD Pipeline

We use **GitHub Actions** for continuous integration. Every push and PR triggers:

- Linting (ESLint / flake8 / phpcs)
- Unit and integration tests
- Build validation
- (On merge to main) Automatic deployment to staging

Do not push directly to `main`. All changes must go through a PR.

### 9. Communication and Process

- Daily standups are held in the team communication channel
- Tag issues and PRs with the right labels and assignees
- Use GitHub Discussions for architectural decisions and longer-form conversations
- For urgent production issues, escalate directly to your team lead

---

## Our Engineering Principles

- **Ship fast, iterate faster** — working software beats perfect software
- **AI-first thinking** — explore AI/LLM solutions before building things manually
- **Open source by default** — our core products are AGPL-licensed and we contribute back
- **Documentation is code** — if it is not documented, it does not exist
- **Security by default** — never commit secrets; use `.env` files and a secret manager
- **Ownership mentality** — you own your features from code to production

---

## Licensing

Our public repositories are released under the [**GNU Affero General Public License v3.0 (AGPL-3.0)**](https://www.gnu.org/licenses/agpl-3.0.html). You are free to use, study, and modify the code — but any modifications must also be released as open source under the same license.

---

<div align="center">

*Built with passion by the Globussoft Technologies team*

</div>
