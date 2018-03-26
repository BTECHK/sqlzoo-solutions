# sqlzoo-solutions
Solutions to the challenges on http://sqlzoo.net
SELECT distinct CASE WHEN per1.date_of_birth <= TO_DATE('12-31-1942',mm-dd-yyyy) THEN 'Tradistionalists'WHEN per1.date_of_birth between TO_DATE('12-31-1942',mm-dd-yyyy) and TO_DATE('12-31-1960',mm-dd-yyyy) THEN 'Babyboomers'WHEN per1.date_of_birth between TO_DATE('12-31-1960',mm-dd-yyyy) and TO_DATE('12-31-1981',mm-dd-yyyy) THEN 'Generation Xers'else 'Milennials'endfrom per_persons per1
