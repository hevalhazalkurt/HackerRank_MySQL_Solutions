# 005 - Japanese Cities' Attributes

<br>

## Problem

Query all attributes of every Japanese city in the `CITY` table. The `COUNTRYCODE` for Japan is `JPN`.


## Input Format

The `CITY` table is described as follows :

![](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

---

## Solution

```SQL
SELECT * FROM CITY WHERE COUNTRYCODE = "JPN"
```

<br>

**Output**

```
1613 Neyagawa JPN Osaka 257315
1630 Ageo JPN Saitama 209442
1661 Sayama JPN Saitama 162472
1681 Omuta JPN Fukuoka 142889
1739 Tokuyama JPN Yamaguchi 107078
```
