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

## SQL Scripts
All SQL scripts are included in the repository. These scripts cover:
- Dropping and creating tables
- Inserting data into tables
- Executing select queries
- Creating database views

## Screenshots
Oracle APEX screenshots demonstrating the output of the SQL scripts are included in the repository.
