# Speaker notes (about 8–9 minutes)

## Slide 1 — Title (30 sec)
Hi everyone. My project is about learning engagement and student performance. I looked at recorded activity in the Open University’s online learning environment and how it is associated with final course outcomes.

## Slide 2 — Project and questions (60 sec)
The dataset has about 10.65 million daily interaction records and 32,593 student-course registrations. The project asks five questions: which outcomes are most common, how clicks differ by outcome, how activity changes weekly, which material types receive the most clicks, and whether engagement patterns differ across modules. A registration is a student taking a course presentation, so it is not always a unique person.

## Slide 3 — Method (60 sec)
The original interaction file is large, so I processed it in chunks rather than loading it all into memory. I linked daily interactions to student-course information and to the types of VLE materials. Then I created summaries at registration, week, activity type and module level.

## Slide 4 — RQ1 (50 sec)
Pass was the most common outcome, with 12,361 registrations, or 37.9%. There were 10,156 withdrawals, 7,052 fails and 3,024 distinctions. This gives an overview of the outcome distribution in these selected courses.

## Slide 5 — RQ2 (60 sec)
Mean recorded clicks were highest for Distinction registrations at 2,666.8, followed by Pass at 1,921.8, Fail at 651.9 and Withdrawn at 314. The notebook uses a box plot and a log scale because click counts are highly skewed. This is an association, not proof that more clicks cause a better result.

## Slide 6 — RQ3 (60 sec)
Week 1 had the highest average activity, at 127.7 clicks per registration. Activity then changes across the course, and the lines differ by final outcome. One possible explanation is that the first week includes initial course exploration, but this dataset alone does not prove that explanation.

## Slide 7 — RQ4 (50 sec)
The most-clicked VLE material type was oucontent, with 11,206,803 clicks. Forumng, quiz and homepage were also used frequently. This shows where recorded interactions were concentrated, not which material helped students learn the most.

## Slide 8 — RQ5 (60 sec)
The heatmap shows that mean clicks vary across course modules and outcomes. The highest mean shown was 5,198.4 for FFF Distinction, while the lowest was 97.8 for GGG Fail. Modules can differ in their structure and design, so these differences need to be interpreted carefully.

## Slide 9 — Additional view (45 sec)
This scatter plot is an extra exploratory analysis. Most registrations had zero previous attempts, and engagement varies substantially within each attempt group. It is included to show another possible relationship, not to claim a causal effect.

## Slide 10 — Conclusion (60 sec)
Overall, recorded engagement and final outcomes show patterns in this dataset. However, clicks do not measure attention or understanding, students may appear in more than one registration, and the data is observational. The main takeaway is that online activity can help describe participation, but it should not be treated as a direct measure of learning. Thank you.
