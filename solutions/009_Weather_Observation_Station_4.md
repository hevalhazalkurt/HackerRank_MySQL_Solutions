# 009 - Weather Observation Station 4

<br>

## Problem

Let N be the number of `CITY` entries in `STATION`, and let `N'` be the number of distinct `CITY` names in `SATATION`; query the value of `N - N'` from `STATION`. In other words, fin dthe difference beetween the total number of `CITY` entries in the table and the number of distinct `CITY` entries in the table.


## Input Format

The `STATION` table is described as follows :

![](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where `LAT_N` is the northern latitude and `LONG_W` is the western longitude.

<br>

---

## Solution


```SQL
SELECT COUNT(CITY) - COUNT(DISTINCT CITY) AS N FROM STATION
```

<br>

**Output**

```
13
```
