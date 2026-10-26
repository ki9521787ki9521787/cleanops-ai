# CleanOps AI

AI-powered operations platform for cleaning businesses, janitorial teams, recurring service companies, and commercial maintenance providers.

CleanOps AI helps cleaning businesses manage bookings, assign teams, monitor quality, track recurring jobs, and reduce operational overhead with a single operating system.

## Why it matters

The cleaning industry is operationally messy:

- bookings come from phone, web, and text
- schedules are created manually
- staff availability is inconsistent
- quality checks are not standardized
- recurring jobs are hard to track
- invoices and follow-ups are delayed
- business owners do not see performance clearly

CleanOps AI centralizes these workflows into a single service-control layer.

## Product vision

CleanOps AI is an operations OS for service teams with:

- booking management
- workforce scheduling
- recurring service planning
- quality control workflows
- route and zone planning
- customer communication
- invoice and payment visibility
- AI recommendations for staffing and retention

## Core features

- dashboard with KPIs
- booking and customer management
- team planner and shift scheduling
- quality checklist templates
- recurring service workflows
- service history and customer notes
- invoicing and payment tracking
- AI-powered staffing and repeat-order suggestions

## Ideal customers

- residential cleaning companies
- commercial janitorial teams
- property cleaning providers
- recurring service businesses
- facilities maintenance brands

## Tech stack

- Backend: Python, FastAPI
- Frontend: Next.js, TypeScript, React
- Database: PostgreSQL-ready with SQLite for MVP
- Services: Redis, Docker

## Commercial model

- monthly SaaS subscriptions
- per-location pricing
- setup and onboarding add-ons
- custom reporting and branded clients
- premium analytics and AI modules

## Local development

### Backend

```bash
cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

### Frontend

```bash
cd frontend
npm install
npm run dev -- --host
```

### Docker

```bash
docker-compose up --build
```

## Project structure

```text
backend/
  app/
  requirements.txt
frontend/
  src/
docker-compose.yml
README.md
LICENSE
```

## Roadmap

- multi-location support
- recurring job automation
- AI quality scoring
- customer retention flow
- invoice and payment sync
- team performance analytics

## Contact

- Email: ki9521787@gmail.com
- GitHub: https://github.com/ki9521787ki9521787/cleanops-ai

## License

This project is for commercial SaaS use and can be adapted to specific cleaning business workflows.
