# SQL

MySQL is from oracle
SQL server is from microsoft

# always use group by when ever u use aggregate functions

# learn differnce btwn inner join , natural join , equi join

# join
- 'on' clause is must
- by default performs inner join ( returns matching rows form both tables ....based on condition given in 'on' clause
- on clause can have any operator ..  = > < !=  

# natural join

- 2 tables must have atleast 1 column with same name
- no need of 'on' clause
- becuase by befault it will combine tables based on column that have same name

# - natural join and inner join will have same result when the coulum used in 'on' clause of inner join use columns having same name
# - natural join and equi join will have same result when the inner join uses '=' in 'on' clause.

# equi join

- can have only = in 'on' clause
- same returns matchin rows ..like inner join

# MySQL functions

# data function 
     DATE_ADD(date_col, INTERVAL 1 DAY)
     DATE_ADD(date_col, INTERVAL -5 DAY)
     DATE_ADD(date_col, INTERVAL 2 MONTH)
     DATE_ADD(date_col, INTERVAL 1 YEAR)
     
# round off
     round( float_numbr_colum , no_of_decimal_u_want)

 # case when ' ' = ' ' then 1 else 0 end 
     sum( case when coln_name = 5 then 1 else 0 end)  ----->   used to find count of coln_n when its value is something(5)
     
     
