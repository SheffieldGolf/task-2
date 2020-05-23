# task-2

## System
* golf_system_0:  using word embedding to construct document vector and calculate similarity by four features including cosine sim and euclidean distance.

* golf_system_1:  introducing TF-IDF cosine similarits (tweet VS vclaim_content, tweet VS vclaim_title) and BM25 scores (tweet VS vclaim_content, tweet VS vclaim_title) as features, Linear SVC as model

* golf_system_2:  introducing TF-IDF cosine similarits (tweet VS vclaim_content, tweet VS vclaim_title) and BM25 scores (tweet VS vclaim_content, tweet VS vclaim_title) as features, Logistic Regression as model

## Result
BaseLine:  
| metric | @depth | score |
| --- | --- | --- | 
| map | 1 | 0.470 |
| map | 3 | 0.601 |
| map | 5 | 0.609 |
| map | 10 | 0.615 |
| map | 20 | 0.617 |
| map | all | 0.619 |
| precision | 1 | 0.472 |
| precision | 3 | 0.249 |
| precision | 5 | 0.156 |
| precision | 10 | 0.082 |
| precision | 20 | 0.043 |
| precision | all | 0.000 |
| reciprocal_rank | 1 | 0.472 |
| reciprocal_rank | 3 | 0.603 |
| reciprocal_rank | 5 | 0.611 |
| reciprocal_rank | 10 |  0.616 |
| reciprocal_rank | 20 | 0.619 |
| reciprocal_rank | all | 0.621 |
 
 System 1:  
| metric | @depth | score |
| --- | --- | --- | 
|             map|      1 | 0.622|
|             map|      3 | 0.622|
|             map|      5 | 0.622|
|             map|     10 | 0.622|
|             map|     20 | 0.622|
|             map|    all | 0.622|
|       precision|      1 | 0.624|
|       precision|      3 | 0.208|
|      precision|      5 | 0.125|
|      precision|     10 | 0.062|
|      precision|     20 | 0.031|
|      precision|    all | 0.000|
|reciprocal_rank|      1 | 0.624|
|reciprocal_rank|      3 | 0.624|
|reciprocal_rank|      5 | 0.624|
|reciprocal_rank|     10 | 0.624|
|reciprocal_rank|     20 | 0.624|
|reciprocal_rank|    all | 0.624|
 
 System 2:  
| metric | @depth | score |
| --- | --- | --- | 
|            map|      1 | 0.612|
|            map|      3 | 0.612|
|            map|      5 | 0.612|
|            map|     10 | 0.612|
|            map|     20 | 0.612|
|            map|    all | 0.612|
|      precision|      1 | 0.614|
|      precision|      3 | 0.205|
|      precision|      5 | 0.123|
|      precision|     10 | 0.061|
|      precision|     20 | 0.031|
|      precision|    all | 0.000|
|reciprocal_rank|      1 | 0.614|
|reciprocal_rank|      3 | 0.614|
|reciprocal_rank|      5 | 0.614|
|reciprocal_rank|     10 | 0.614|
|reciprocal_rank|     20 | 0.614|
|reciprocal_rank|    all | 0.614|
 
