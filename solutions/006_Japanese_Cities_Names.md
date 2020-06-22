# 006 - Japanese Cities' Names

<br>

## Problem

Query all names of every Japanese city in the `CITY` table. The `COUNTRYCODE` for Japan is `JPN`.


## Input Format

The `CITY` table is described as follows :

![](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

---

## Solution

```SQL
SELECT NAME FROM CITY WHERE COUNTRYCODE = "JPN"
```

<br>

**Output**

```
Neyagawa
Ageo
Sayama
Omuta
Tokuyama
```
