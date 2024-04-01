#    Table Of Contents
1. [SELECT](#part1)
2. [SELECT WITH IF](#part2)
3. [INNER JOIN](#part3)
4. [ORDER BY](#part4)
5. [CREATE USER](#part5)
6. [GRANT ROLL](#part6) 
    1.[ROLL LIST](#part6.1)
8. [SHOW GRANTS](#part7)
9. [REVOKE](#part8)
10. [SAVE](#part9)
11. [LOAD](#part10)

<a name="part1"></a>
##    SELECT 
```cpp
SELECT <columns> FROM <table>
```

<a name="part2"></a>
##    SELECT WITH IF 
```cpp
<SELECT...> WHERE <column> = <num/string> 
```

```cpp
<SELECT...> WHERE <column> LIKE 'char%'
```

<a name="part3"></a>
##    INNER JOIN
```cpp
SELECT <columns> FROM <table1> INNER JOIN <table2> ON <table1.column> = <table2.column> INNER JOIN... 
```

<a name="part4"></a>
##    ORDER BY
```cpp
ASC:  upper
DESC: lower
```

```cpp
ORDER BY <colummn> ASC/ DESC
```

<a name="part5"></a>
##    CREATE USER
```cpp
CREATE USER <name> IDENTIFIED BY <password>
```

<a name="part6"></a>
##    GRANT ROLL
```cpp
GRANT <roll_name> ON <table> TO <name>
```

<a name="part6.1"></a>
#### roll list (typical):
* INSERT
* CREATE
* ALTER
* DROP
* SELECT
* UPDATE
* ALL
* DELETE

<a name="part7"></a>
##   SHOW GRANTS
```cpp
SHOW GRANTS FOR <name>
```

<a name="part8"></a>
##    REVOKE
```cpp
REVOKE <roll_name> ON <table> FROM <name>    
```

<a name="part9"></a>
##    SAVE .sql
* step 1: Tools
* step 2: export database as SQL
* step 3: select table
* step 4: select browse and set file name
* step 5: Export

<a name="part10"></a>
##    LOAD .sql
* step 1: File
* step 2: Load SQL file...

![Screenshot 2024-04-01 164138](https://hackmd.io/_uploads/rJolzW_JR.png)
![heidi](https://hackmd.io/_uploads/SkkYzZOyR.jpg)

