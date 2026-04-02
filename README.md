Here creating new tables like customer and orders

1.bronz_layer
   --> getting the data from source and load into bronz using autolader 
2.silver_layer
   -->here we are doing some transformation like removing duplicate and nulls and spiliting the columns as well
   --> storing the data into silver layer
3.gold_layer
   --> here we are some aggrigation and creating the fact and dim table in gold layer
   --> creating the scd1 & scd2 loading the data into cus_dim & or_fact
   -->finally loading into gold layer
