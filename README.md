# Cobot Fault Analysis

End-to-end data analysis of operational sensor data from a UR3 collaborative
robot arm, focused on understanding what happens when the robot makes
a protective stop or loses its grip.

> **Status:** work in progress

## Dataset

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

(to be completed)

## Key Findings

(to be completed)

## How to Run

(to be completed)