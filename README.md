# sql-test
Simple database setup. Tested on Oracle 11g XE.

## TABLE_1 (persons)

MemberId | Name   | Address | Mesto  | Sex    | BirthDate
-------- | ------ | ------- | ------ | ------ | ---------
Int      | String | String  | String | M or W | Date

## TABLE_2 (payments)

MemberId | Date   | Amount  
-------- | ------ | ------- 
Int      | Date   | Decimal

## Queries
- Total income for each person
- Persons with total income over 500
- Total income for persons over 30 y.o.

## Notes
1. 31.06.2007 is not a valid date. No details were given, so I used 30.06.2007 instead.
2. For `Amount` column I used NUMBER datatype becauses it provides best precision for finance.
