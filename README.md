# BB20 Hype Tracker

A personal Python project to analyze Bigg Boss Hindi season 20 contestants'
social-media hype on X and Instagram, and practice Python through a real application.

## Status

Repository setup only. The application has not been implemented yet.

## Planned first version

- A local Python web dashboard with SQLite storage.
- Clearly labeled fictional demo data and CSV import for real post data.
- Contestant rankings, platform filters, and activity trends.
- A configurable hype score based on post volume and engagement, normalized
  separately for each platform, with the formula visible in the dashboard.

The initial data workflow will use CSV imports. Live platform integrations are
future work and will require the relevant API access. No real contestant list or
live social-media data is bundled with this repository.

## Development

Python 3.13 is available in the current development environment. Dependencies and
run commands will be documented when the application is added.

Keep local datasets in `data/` and generated exports in `exports/`. Both directories
are ignored by Git, along with databases, virtual environments, caches, and `.env`
files. Use `.env.example` to document future configuration without storing secrets.

## Proposed implementation steps

1. Define the post schema and CSV validation rules.
2. Implement SQLite persistence and test the scoring logic.
3. Add the dashboard, filters, and trend charts.
4. Add platform API adapters once access is available.
