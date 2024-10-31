This repository contains data scraped from the GitHub API for users in Berlin with over 200 followers.

**users.csv**: Information about each user.<br>
**repositories.csv**: Information about the public repositories of each user.

In Summary - 

1) Data scraping was performed using the GitHub API, focusing on users from Berlin and their repositories. The relevant user information was extracted into a structured format for analysis.
2) A Interesting finding was that the most common surname among users was Schneider, with only three occurrences. This suggests a relatively low diversity in surnames among the sampled developers.
3) Developers should consider enhancing their profiles and engagement, as hireable users had a marginally lower chance of sharing email addresses. This might suggest potential improvements in networking and job opportunities.

In details - 

Data Scraping Summary
API Requests: Utilized the GitHub API to fetch user data and their repositories for individuals located in Berlin.
Data Filtering: Filtered users based on follower count, hireable status, and account creation dates.
Data Storage: Compiled the relevant data into CSV files for analysis, utilizing Pandas for data manipulation.<br><br>
Interesting Finding
The most common surname identified was "Schneider," which had only three users associated with it. This indicates a limited representation of surnames among developers in Berlin, potentially reflecting broader trends in the local tech community or demographic.<br><br>

Actionable Recommendation
To increase visibility and hiring opportunities, developers should prioritize creating comprehensive profiles, including email addresses, and actively participating in open-source projects. This is particularly important as hireable users had a slightly lower tendency to share their emails, indicating potential areas for improvement in professional networking.
