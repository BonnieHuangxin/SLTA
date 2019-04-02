# Cross-Modal Video Moment Retrieval with Spatial and Language-Temporal Attention
This is our implementation for the paper:

Bin Jiang, Xin Huang, Chao Yang and Junsong Yuan. 2019. Cross-Modal Video Moment Retrieval with Spatial and Language-Temporal Attention.  In <em>Proceedings of the 2019 ACM on International Conference on Multimedia Retrieval</em>. ACM, 2019.

To well align the given textual query and the video moment candidates, we devise a spatial and language-temporal attention model to adaptively identify the relevant objects and interactions based on the query information.

**Please cite our ICMR'19 paper if you use our codes. Thanks!** 

## Environment Settings
We use the framework pytorch. 
- tensorflow version:  '1.7.0'
- python version: '3.6'

## Example to run the codes.

Run SLTA:

```
SLTA.ipynb
```

After training process, the value of "R@n, IoU=m" in the test dataset will be printed in command window after each optimization iteration.

Output:

```
AGREE at embedding size 32, run Iteration:30, NDCG and HR at 5
...
User Iteration 10 [449.8 s]: HR = 0.6216, NDCG = 0.4133, [1.0 s]
Group Iteration 10 [471.9 s]: HR = 0.5910, NDCG = 0.4005, [23.0 s]

```

