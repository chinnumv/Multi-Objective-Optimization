# Course Assignment Optimization using NSGA-II

This code implements a multi-objective optimization problem for course assignment using the NSGA-II algorithm. The goal is to assign courses to users in a way that maximizes engagement, minimizes prerequisite violations, ensures diversity of topics, and respects user preferences.

## Problem Definition

The problem is formulated with four objectives:

- Maximize User Engagement: This objective aims to maximize user engagement metrics such as completion rate and interaction time.
- Minimize Prerequisite Violations: This objective minimizes the number of violated prerequisites for assigned courses.
- Ensure Diversity of Topics: This objective promotes the coverage of a diverse range of topics by minimizing the number of unique topics covered.
- Respect User Preferences: This objective aims to match course content with user preferences.

## Usage

### To run the optimization:

- Install the required dependencies (numpy, pymoo).
- Execute the provided Python script course_assignment_optimization.py.
- Adjust parameters such as population size and termination criteria as needed.
- View the Pareto front visualization to explore the trade-offs between objectives.

## Dependencies

- numpy: Required for numerical operations.
- pymoo: Python library for multi-objective optimization.

## References

- pymoo documentation
 