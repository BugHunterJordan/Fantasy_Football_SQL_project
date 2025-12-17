# Fantasy Football War Room League

## Project Overview
This project is a database for managing a fantasy football league. It stores league teams, team records, and standings. The project was created for my SQL course final project using SQL in Oracle APEX.

## Database Design
- **Tables:**
  - `Teams` – stores 12 teams with TeamID, TeamName, and OwnerName.
  - `Records` – stores wins and losses per team.
  - `Standings` – stores ranking and points for each team.

- **Relationships:**
  - Teams → Records (1:M)
  - Teams → Standings (1:M)
  - Records → Standings (1:1)

- **Views:**
  - `seeTeams`
  - `seeRecords`
  - `seeStandings`

## Scripts
All SQL scripts are in the `SQL/` folder:
- `create_tables.sql` – creates the database tables
- `insert_data.sql` – populates tables with sample data
- `select_queries.sql` – contains select and extra queries
- `views.sql` – contains view creation scripts

## Screenshots
Oracle APEX screenshots are in the `Screenshots/` folder.

## Usage
1. Open Oracle SQL Developer or Oracle APEX.
2. Run the scripts in the following order:
   - `create_tables.sql`
   - `insert_data.sql`
   - `views.sql`
   - `select_queries.sql`
3. Check the screenshots to see expected output.
