# Cobot Fault Analysis

End-to-end data analysis of operational sensor data from a UR3 collaborative
robot arm, focused on understanding what happens when the robot makes
a protective stop or loses its grip.

> **Status:** work in progress

## Dataset
- Column names were standardized (lowercase, no spaces). `Temperature_T0` was renamed to `temperature_j0`, assuming it is a typo of the J0 column.
- 54 rows with missing sensor values or labels were removed (0.7% of the data).
- Units are not documented by the data source.

- **Source:** UR3 CobotOps dataset, UCI Machine Learning Repository
  (https://archive.ics.uci.edu/dataset/963/ur3+cobotops), CC BY 4.0
- **Size:** 7,409 rows and 24 columns, sampled about once per second
- **Content:** motor current, temperature and speed of the six robot joints
  (J0 to J5), gripper current, task cycle counter, and two event labels
  (`Robot_ProtectiveStop`, `grip_lost`)

## Tools

Python (pandas, Matplotlib, Seaborn), SQLite and SQL, Power BI

## Project Structure

(to be completed)

## Analysis Questions

1. How many protective stop and grip loss events occur, and how long does each last?
2. How are these events distributed across work cycles?
3. Which joint carries the highest electrical load?
4. How does joint temperature evolve over time and across cycles?
5. How do joint currents and speeds differ during a protective stop compared to normal operation?
6. How do gripper current and joint behavior differ during a grip loss?
7. Which sensor variables are most strongly associated with the events?

## Key Findings

(to be completed)

## How to Run

(to be completed)