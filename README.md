# SQL Server Self-Study Scripts

This repository contains SQL Server scripts created during self-study while following Baraa's [SQL Full Course for Beginners (30 Hours) – From Zero to Hero](https://www.youtube.com/watch?v=SSKVgrwhzus). It is structured as a personal learning and revision repository that combines the original reference scripts from the course with a separate personal master script for active learning, annotations, and long-term revision.

## Purpose of this repository

This repository exists to make SQL Server revision easier, clearer, and more practical over time.

The original course scripts are useful for syntax reference and for seeing the commands taught in each chapter. However, for repeated revision, trial-and-error learning, and concept retention, a single continuously updated script with personal notes and structure is much more useful.

That is the role of the **Master Script** in this repository.

## Repository structure

```text
repo-root/
│
├── data with bara scripts/
│   ├── init-sqlserver-salesdb.sql
│   ├── init-sqlserver-mydatabase.sql
│   ├── chapter-wise scripts
│   └── other reference scripts from the course
│
└── Master Script.sql
```

## What is inside the `data with bara scripts` folder

The `data with bara scripts` folder contains Baraa's course-based reference scripts.

### Setup scripts

The setup scripts that should be run first whenever required are:

- `init-sqlserver-salesdb.sql`
- `init-sqlserver-mydatabase.sql`

These scripts prepare the required database objects that later examples may depend on.

### Chapter-wise scripts

The rest of the scripts are organized chapter-wise and should be used mainly as a reference source for syntax and course examples.

## What is `Master Script.sql`

`Master Script.sql` is the main personal study script in this repository.

It is a continuously updated script that brings the course into one connected learning file instead of leaving the material fragmented across many chapter scripts.

Compared with the original reference scripts, the Master Script is more useful for revision because it includes:

- personal comments,
- timestamps for backtracking to the video,
- better structure across topics,
- cleaner continuity from one concept to the next,
- revision-friendly formatting,
- small reminders for common mistakes,
- explanatory notes that make rereading easier than going back through raw notes alone.

It follows the broader chronology of the course, moving through foundational SQL into intermediate and advanced topics, and later into project-based work.

### Course chronology followed in the Master Script

Source video: [SQL Full Course for Beginners (30 Hours) – From Zero to Hero](https://www.youtube.com/watch?v=SSKVgrwhzus)

#### 🟢 Beginner Level

- `00:00` Intro
- `07:38` Introduction to SQL
- `22:33` Setup Your Environment
- `34:01` Query Data (SELECT)
- `01:32:31` DDL Commands
- `01:43:44` DML Commands

#### 🟡 Intermediate Level

- `02:08:03` Filtering Data
- `02:47:57` SQL Joins (Basics)
- `03:27:29` SQL Joins (Advanced)
- `04:02:09` Set Operators
- `04:47:41` SQL Functions
- `04:52:58` String Functions
- `05:18:44` Numeric Functions
- `05:22:48` Date and Time Functions
- `06:59:06` NULL Functions
- `08:07:50` Case Statement
- `08:43:36` Aggregate Functions
- `08:50:11` Window Functions Basics
- `09:47:00` Window Aggregate
- `10:53:09` Window Ranking
- `11:56:05` Window Value

#### 🔴 Advanced Level

- `12:40:34` Advanced SQL Techniques
- `12:58:04` Subqueries
- `14:18:08` Common Table Expressions (CTE)
- `15:35:02` Views
- `16:36:40` CTAS and Temp Tables
- `17:17:31` Compare Advanced Techniques
- `17:27:04` Stored Procedures
- `18:12:58` Triggers
- `18:23:42` Indexes
- `20:20:31` Execution Plan
- `21:11:03` Partitions
- `21:43:39` 30x Performance Tips
- `22:24:25` AI and SQL

#### 🧪 Projects

- `23:21:04` Project: SQL Data Warehouse
- `24:32:54` Project DWH | Bronze
- `25:10:09` Project DWH | Silver
- `26:47:46` Project DWH | Gold
- `27:41:51` Project: Exploratory Data Analysis (EDA)
- `28:30:38` Project: Advanced Data Analytics
- `29:47:24` Thank You

## How to use this repository

To avoid confusion and frustration, it is important to follow the correct order.

### Learning flow

```text
Start
  |
  v
Open README
  |
  v
Go to data with bara scripts/
  |
  v
Run the required setup scripts first
(init-sqlserver-salesdb.sql / init-sqlserver-mydatabase.sql)
  |
  v
Open the relevant chapter-wise script when needed
(for syntax and course reference)
  |
  v
Then open Master Script.sql
  |
  v
Use it for connected learning, revision, comments, and timestamp-based backtracking
  |
  v
Practice / revise / extend over time
```

## Important note

If a user wants the original teaching sequence and syntax examples, the scripts inside `data with bara scripts` should be used as the first reference point.

If a user wants a more revision-friendly and connected study experience, `Master Script.sql` should be the main script to follow after the required setup scripts are run.

## Attribution

The original learning source for this repository is Baraa's 30-hour SQL Server course and its supporting scripts.

Credit for the teaching material, topic sequence, and original reference scripts belongs to Baraa.

This repository does not claim ownership over the original course material. Instead, it preserves that learning reference while also adding a separate personal study layer through annotations, comments, timestamps, restructuring, and revision improvements.
