# GymFlow Console

Web console for GymFlow, a MySQL database for tracking fitness club members and their workouts (EDS 6343, Team 05).

**Live site:** https://siddhardhaanagani69-ship-it.github.io/gymflow-console/

The hosted version runs on a saved snapshot of the database (`data.json`), so it needs no server. It has four views:

- **Overview:** key numbers and charts
- **Members:** a searchable directory
- **Schema & rules:** the table design, plus forms that test the database's integrity rules
- **Query Pack:** the 17 SQL queries and their results

Click **▶ Play demo** for a guided walkthrough.

Changes made in the forms stay in the browser and reset when you reload. Running the console against a live MySQL database needs the local `server.py` from the main project repository.
