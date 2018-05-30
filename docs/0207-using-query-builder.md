---
id: 0207-using-query-builder
title: Using the Query Builder
sidebar_label: Using the Query Builder
---

## Add or Delete Query Builder Table

This section explains how to add or delete tables using query builder.

1. Connect to database.
2. On the main menu bar, go to **File**>**New**>**Query Builder**. Or, simply click [Query Builder].
3. On the main menu bar, go to **View**>**Object Panel**. Or, simply click [Object Panel] on the New Toolbar or press F12.
4. From the Object Panel, select a table and drag it to the query builder window.
![Add tables to query builder on object panel](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/19E5C591A4FD401B062E756EAA2004EF.jpg)
5. Check the added tables. To delete, right-click and select [Delete].
![Delete tables from query builder](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/7A4208C3014CAF14DEBBF40BE886F431.jpg)
6. Check the result.


## Add Column on Query Builder

This section explains how to add table columns on query builder.

1. Connect to database.
2. On the main menu bar, go to **File**>**New**>**Query Builder**. Or, simply click [Query Builder] on the New Toolbar.
3. On the main menu bar, go to **View**>**Object Panel**. Or, click [Object Panel] on the New Toolbar or press F12.
4. Select tables from the object panel and drag them into the query builder window.
![Add tables to query builder on object panel](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/F1D37BE6232783D921276E27C243F148.jpg)
5. Select table columns to show.
![Add table columns to query builder](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/CA148052A99D1287C03E3B8C8763A85E.jpg)
6. Check the autogenerated query in SQL tab.
![Check the added table columns in query builder](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/0F875874F8B7B5490EBE16B817B724CC.jpg)


## Create JOIN Between Tables

This section explains how to create JOIN between tables on query builder.

1. Connect to database.
2. On the main menu bar, go to **File**>**New**>**Query Builder**. Or, click [Query Builder] on the New Toolbar.
3. On the main menu bar, go to **View**>**Object Panel**. Or, click [Object Panel] on the New Toolbar or press F12.
4. On Object Panel, select the tables and drag them to the query builder window.
![Add tables from object panel to query builder](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/F1D37BE6232783D921276E27C243F148.jpg)
5. Select table columns to show.
![Select columns to show on table](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/CA148052A99D1287C03E3B8C8763A85E.jpg)
6. Choose related columns and drag them to a column of another table.
7. Right-click Link and select [Property].
![Drag related fields to tables](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/6E13814ECE514320351239915B801BA1.jpg)
8. Enter values in ‘Link Properties’ window. Click [OK].
![JOIN tables](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/38A5E80FF0B9AC33E41EC9B447954AB7.jpg)
9. Check the result of autogenerated queries on SQL tab.
![Check autogenerated queries on SQL tab](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/B4B85D41B1EC2786324ED33C1CA5B760.jpg)
10. Click [Run] or press F5.
11. Check query result on the result tab.
![Check the JOINed tables](https://s3.ap-northeast-2.amazonaws.com/sqlgate-manual-content/FF8239EF7AD948B6AC8EE7F9EDF68744.jpg)

> Tip: To set Table Alias, double-click the table name and give it an alias.