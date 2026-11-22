# Course Scheduling Optimization

This project formulates spring course selection for a second-year Data Analytics student at The Ohio State University as a binary optimization problem. The model selects course sections to maximize the sum of instructor ratings while accounting for degree requirements, a 12–18 credit load, and time conflicts on shared meeting days.

- [Optimization notebook](project_code.ipynb) — prepares the section data, builds the model with CVXPY, and solves it with Gurobi. The notebook includes the solver output.
- [Course and instructor data](Course_Instructor.csv) — section meeting times, credit hours, instructor ratings, and general education indicators used by the model.

Final project for ISE 3230, Autumn 2023, at The Ohio State University.

**Contributors** · Ana Xiong, Brittany Araujo, and Manasa Subramanian.
