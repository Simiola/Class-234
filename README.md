# Class-234

(select city,country from customers where country = 'USA' or country='Brazil')
  union all
 (select city,country from suppliers where country = 'USA' or country='Brazil')


 (select * from suppliers)
union
(select * from company_products)
