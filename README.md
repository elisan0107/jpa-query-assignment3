# jpa-query-assignment3

- [x] Don't forget coffee!
- [x] You need to have four classes: Student, Tutor, Subject, and Address for this assignment.
- [x] Confirm the relationship between Tutor and Student is One to Many.
- [x] Confirm the relationship between Tutor and Subject is Many to Many.
- [x] Download Hibernate template

To refresh your knowledge, look at the images and workshops on queries-1, queries2, and queries3.

## Task 1 - Navigating Relationships (using member of)
- [ ] Write a query to get the names of all students whose tutor can teach science.
- [ ] We can write this query in different ways. But what we want here is to use `member of`.
- [ ] The students should be fetched from the query. Then you can use a 'for each loop' to print them out.
  - [ ] This is not accepted if you find the tutor through the query and then find the students for that specific tutor using Java methods.

🔴 **Important Note:** 
What we want is to get **the names of ALL (?) students** whose tutor can teach, for example, science.

![My Picture](img.png)

## Task 2 - Report Query - Multiple Fields (using join)
- [ ] Write a query to fetch the **names of all students** and **the names** of their **tutors**.

🔴 **Important Note:** There are different ways to do this. But here, we want you to use a report query (SQL) by using `join`.

## Task 3 - Report Query - Aggregation
- [ ] Use aggregation to get the average semester length for the subjects.

## Task 4 - Query with Aggregation
- [ ] Write a query that can return the maximum salary from the tutor table.

## Task 5 - Named Query
- [ ] Write a named query that can return all tutors with a salary higher than 10,000.

🔴 **Important Note:** What is a named query?

## Finally
- [ ] Send your GitHub link to Google Classroom.
