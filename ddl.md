create table SANDWICHES
(
ID          NUMBER(30) not null
constraint SANDWICHES_PK
primary key,
NAME        VARCHAR2(100),
DESCRIPTION VARCHAR2(100),
CATEGORY    VARCHAR2(100),
BASEPRICE   FLOAT
)
/