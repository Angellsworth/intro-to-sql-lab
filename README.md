# 🕵️‍♀️ Intro to SQL Lab: Where in the World is Carmen Sandiego?

Welcome, gumshoe. You’ve just entered a world of **data sleuthing**, international chases, and crafty SQL queries. Your mission? To **track down Carmen Sandiego** using nothing but your wit, a relational database, and some clean code.

> 💽 Powered by PostgreSQL + your brain.

---

## 🌍 About This Lab

In this lab, you’ll write SQL queries against a `world` database to trace Carmen Sandiego’s steps across countries, languages, and cities.

You’ll learn to:

- 🛠 Create & query real SQL tables (`countries`, `cities`, `languages`)
- 🧠 Filter with `WHERE`, `AND`, `ORDER BY`, and `LIMIT`
- 🔗 Join data across multiple tables
- 👀 Analyze clues with logic and pattern-matching

---

## 🧠 Learning Goals

| Concept | Skills Practiced |
|--------|------------------|
| SQL Queries | `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `JOIN`, `LIMIT` |
| Data Structures | Understanding tables, rows, and relationships |
| Problem Solving | Following clues to find exact data |
| Real-World Application | Navigating relational data like a data analyst |

---

## 🚀 How to Run This Lab

> Make sure you’ve installed PostgreSQL and you're in the right project folder!

### 1. Setup the `world` database:

```bash
psql -f world.sql

This creates your database, tables, and loads it with thousands of rows of real(ish) world data.

2. Solve Carmen’s clues:

Write your answers in clues.sql, one clue at a time.

To test your solutions:

psql -f clues.sql -d world

3. View tables in the terminal:

Start a Postgres session:

psql -d world

Then type:

\d

…to see tables, and:

SELECT * FROM countries LIMIT 10;

…to peek inside.

⸻

🏁 Progress Tracker

Clue	Status	Solved Info
#1	✅ Done	Vatican City, population 1000
#2	✅ Done	Italian is the official language
#3	✅ Done	Carmen went to San Marino
#4	✅ Done	She flew to Serravalle
#5	✅ Done	Switched to “Serra” in Brazil
#6	✅ Done	Headed to Brazil’s capital: Brasília
#7	🧩 In Progress	Find the city with a population of 91,085


⸻

🗺️ Author

Made with ✨ and SQL by @Angellsworth

⸻


