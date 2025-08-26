Here i will use prophet to forecast the sales of various products, but since the product descrpition is a nominal variable with high cardinality, 
I will clusterize products into families, based in the co-occurance frequency, using fp-growth, and then I will create a prophet model to predict each product family sales
