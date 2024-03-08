Selec Year count(Purchased_At)as [2017 Total Purchased At ]
From shawarma_purchases
Where purchased_At IN ('2017-01-01', '2017-12-31')
Group by Year 
## Comparisons vs. Functions

1. Improve the following query

```
SELECT COUNT(purchased_at)
FROM shawarma_purchases
WHERE purchased_at BETWEEN '2017-01-01' AND '2017-12-31';
```
