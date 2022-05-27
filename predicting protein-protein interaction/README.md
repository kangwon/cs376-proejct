EXPERIMENT1 : We experiment how model structure can improve performance 
- experiment1_1 : base matrix factorization model 
- experiment1_2 : matrix factorization model with bias terms 

EXPERIMENT2 : We experiment what are benefits to use a matrix factorization model for PPI predictions 
- experiment2_1 : baseline model(neural network) for the small dataset 
- experiment2_2 : baseline model(neural network) for the large dataset(Note that we fail to train the model because of a lack of RAM) 
- experiment2_3 : matrix factorization model with bias terms for the small dataset

EXPERIMENT3 : We experiment how providing additional information can improve performance
- experiment3_1 : protein subcellular location embedding for base matrix factorization model 
- experiment3_2 : protein subcellular location embedding for matrix factorization model with bias terms 

EXPERIMENT4 : We experiment how negative sampling can improve performance 
- experiment4_1 : training baseline model with randomly chosen 8,000 positive pairs and 2,000 negative pairs of proteins 
- experiment4_2 : training matrix factorization model with bias terms with randomly chosen 8,000 positive pairs and 2,000 negative pairs of proteins 
- experiment4_3 : matrix factorization model with negative sampling1(randomly chosen)
- experiment4_4 : matrix factorization model with negative sampling2(based on frequencies of each protein in pairs) 
