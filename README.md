# University-Success-Analysis
This Is My Capstone Project

Problem Statement
Compare university rankings across different systems, assess the impact of ranking criteria on university positions, and analyze changes in university metrics over time. Utilize SQL and Excel for data aggregation and for EDA. Create a Power BI dashboard to provide a comprehensive view of university rankings.

Dataset Description
This dataset contains information on university rankings from different systems, ranking criteria, and university-specific data.

Table Explanations
country
This is a simple list of countries that were in the data set. I don’t think it’s a complete list of all countries, but it’s enough for this data set.

university
A list of universities that were ranked in this system. Each university is related to a country.

ranking_system
This contains the three different ranking systems used: Times Higher Education World University Ranking, Shanghai Ranking, and Center for World University Rankings.

ranking_criteria
This table contains the different criteria used in each ranking system, such as Citations and Quality of Education. It also contains criteria for Total Score for each system.

university_year
The university_year table contains values for measurements such as the number of students and the student to staff ratio for each university in several years.

university_ranking_year
This table contains the score for each year for each university and ranking criteria. It’s the largest table in the database.
