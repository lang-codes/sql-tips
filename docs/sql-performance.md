𝗧𝗼𝗽 𝟮𝟬 𝗦𝗤𝗟 𝗾𝘂𝗲𝗿𝘆 𝗼𝗽𝘁𝗶𝗺𝗶𝘇𝗮𝘁𝗶𝗼𝗻 𝘁𝗲𝗰𝗵𝗻𝗶𝗾𝘂𝗲𝘀 

Here is the list of the top 20 SQL query optimization techniques I found noteworthy:

1. Create an index on huge tables (>1.000.000) rows
2. Use EXIST() instead of COUNT() to find an element in the table
3. SELECT fields instead of using SELECT *
4. Avoid Subqueries in WHERE Clause
5. Avoid SELECT DISTINCT where possible
6. Use WHERE Clause instead of HAVING
7. Create joins with INNER JOIN (not WHERE)
8. Use LIMIT to sample query results
9. Use UNION ALL instead of UNION wherever possible
10. Use UNION where instead of WHERE ... or ... query.
11. Run your query during off-peak hours
12. Avoid using OR in join queries
14. Choose GROUP BY over window functions
15. Use derived and temporary tables
16. Drop the index before loading bulk data
16. Use materialized views instead of views
17. Avoid != or <> (not equal) operator
18. Minimize the number of subqueries
19. Use INNER join as little as possible when you can get the same output using LEFT/RIGHT join.
20. Frequently try to use temporary sources to retrieve the same dataset.

Do you know what is 𝗤𝘂𝗲𝗿𝘆 𝗢𝗽𝘁𝗶𝗺𝗶𝘇𝗲𝗿? Its primary function is to determine 𝘁𝗵𝗲 𝗺𝗼𝘀𝘁 𝗲𝗳𝗳𝗶𝗰𝗶𝗲𝗻𝘁 𝘄𝗮𝘆 to execute a given SQL query by finding the best execution plan. The query optimizer takes the SQL query as input and analyzes it to determine how best to execute it. The first step is to parse the SQL query and create a syntax tree. The optimizer then analyzes the syntax tree to determine how to run the query.

Next, the optimizer generates 𝗮𝗹𝘁𝗲𝗿𝗻𝗮𝘁𝗶𝘃𝗲 𝗲𝘅𝗲𝗰𝘂𝘁𝗶𝗼𝗻 𝗽𝗹𝗮𝗻𝘀, which are different ways of executing the same query. Each execution plan specifies the order in which the tables should be accessed, the join methods, and any filtering or sorting operations. The optimizer then assigns a 𝗰𝗼𝘀𝘁 to each execution plan based on the number of disk reads and the CPU time required to execute the query.

Finally, the optimizer 𝗰𝗵𝗼𝗼𝘀𝗲𝘀 𝘁𝗵𝗲 𝗲𝘅𝗲𝗰𝘂𝘁𝗶𝗼𝗻 𝗽𝗹𝗮𝗻 with the lowest cost as the optimal execution plan for the query. This plan is then used to execute the query.

Check in the image the 𝗼𝗿𝗱𝗲𝗿 𝗶𝗻 𝘄𝗵𝗶𝗰𝗵 𝗦𝗤𝗟 𝗾𝘂𝗲𝗿𝗶𝗲𝘀 𝗿𝘂𝗻.

![sql-performance](https://github.com/lang-codes/sql-tips/assets/3424344/1e3f0f32-d682-4415-a85e-1ee61e2a98bf)
