# joins and unions

## joins
- allow us to combine data from multiple tables against common columns
1. inner join - matching values on both tables
2. left join - all values on left table and matching rows on right 
- very commonly used
3. left outer join  - all data on left table excluding matching data on right table
4. right join - similar to left join
5. right outer join - similar to left outer join
6. full join - from both left and right and matched rows where applicable 
7. full outer join - exclude intersections between left and right tables

## cross joins
- creates cartesian product between 2 tables
- every combination of 2 columns will be created in a table
- commonly used with daterange creation 

## self joins
- uses regular joins but to itself
- you typically use a self-join to query hierarchical data or to compare rows within the same table.

# Unions
- not as performant as joins
## Unions
- same columns in 2 tables
- combine them according to some criteria 
- keeps distinct rows 
## Union All
- keep duplicates
## Intersect
- show intersection between 2 tables
## except 
- returns distinct rows from the first (left) query that are not in the output of the second (right) query.