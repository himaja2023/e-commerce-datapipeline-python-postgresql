# e-commerce-datapipeline-python-postgresql
Creating datapipeline using python for e-commerce data from csv file to postgresql 

Got the data from kaggle ecommerce data for price comparing for products from different websites
 step 1:
   Created table in pg-admin(Postgresql) in local server (desktop app) with following query
   CREATE TABLE pricecompare(
 index int,
 sku varchar,
 styleid varchar,
 catalog varchar,
 category varchar,
 weight float,
 TP1 int,
 TP2 int,
 MRP Old int,
 FinalMRPOLD int,
 AjioMRP int,
 AmazonMRP int,
 AmazonFBAMRP int,
 FlipkartMRP int,
 LimeroadMRP int,
 MyntraMRP int,
 PaytmMRP int,
 SnapdealMRP int,
 PRIMARY KEY (index,sku)
);
