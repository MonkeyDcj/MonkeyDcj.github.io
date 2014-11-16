MonkeyDcj.github.io
===================
select id from A where a='1' and b='1'

create table A (
 a char(1),
 b char(1),
 c char(1),
 index (a,b,c)
)

create table A (
 a char(1),
 b char(1),
 c char(1),
 index (b,c,a)
)