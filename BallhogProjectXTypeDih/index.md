---
layout: default
title: Ballhog Project
---

# Ballhog Project

**Authors:** Gabriel Teles and Nathalie Marti

## What this project is
We analyzed COMP110 survey data to see whether students who want more support features, like more pre-lecture videos or a livestream option, also report higher difficulty or lower understanding. We focused on the survey columns pre_lecture_videos and add_livestream and compared them to difficulty and understanding. Our goal was to identify whether increased demand for these support options is associated with students struggling more in the course.

## Key results
- Result 1: As interest in more pre-lecture videos increases (1 → 7), average difficulty increases (about 3.77 → 4.70) and average understanding decreases (about 4.89 → 3.92).
- Result 2: Students who most strongly want a livestream option (7) report higher average difficulty (about 4.60) and lower average understanding (about 3.92) than students who least want it (1), who report lower difficulty (about 3.22) and higher understanding (about 4.56).
- Result 3: The largest group sizes were at the highest response levels (pre_lecture_videos = 7 had n = 179; add_livestream = 7 had n = 201), so the upward difficulty trend at high levels reflects a substantial portion of responses.

## Evidence
<img src="/static/imgs/evidence1.png" alt="Evidence chart 1" width="700">

<img src="/static/imgs/evidence2.png" alt="Evidence chart 2" width="700">

## Reflection
This project went well because we were able to take a clear improvement idea and connect it to specific survey columns, which made the analysis straightforward to implement and interpret. The most difficult part was getting the data pipeline and environment set up correctly in the notebook, especially making sure imports and required packages worked in the correct kernel. Once the data was cleaned and grouped, the trends were consistent and easy to communicate through tables and charts. If we were to improve this project, we would add follow-up questions or additional data to better separate correlation from impact, for example tracking whether students who actually use pre-lecture videos or livestreams report improved understanding over time. Overall, the results support prioritizing pre-lecture videos and a livestream option as targeted support for students reporting higher difficulty and lower understanding.