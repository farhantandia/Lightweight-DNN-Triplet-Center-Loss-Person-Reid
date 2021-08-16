# Lightweight-DNN-Triplet-Center-Loss-Person-Reid
 Lightweight DNN using triplet center loss for Person re-identification benchmark on Market1501 dataset, the triplet center loss is based on this [implementation](https://github.com/popcornell/keras-triplet-center-loss).

## Dependencies
- Tensorflow 2.3
- keras_self_attention
- efficientnet
- tensorflow-addons
- matplotlib
- numpy
- scikit-learn 0.23.1

## Method
I build two types of model, the one that use one-stream network (without temporal block) and the other use two-stream network (requires 1 extension of input dimension), the overall architecture is based on this [model](https://github.com/farhantandia/Lightweight-Multi-Task-DNN-Project-and-Benchmark) but using single output instead of multi-output. The evaluation and dataset is follow the standard of [Market1501 dataset](https://paperswithcode.com/dataset/market-1501#:~:text=Market%2D1501%20is%20a%20large,Deformable%20Part%20Models%20pedestrian%20detector.).

## Results
<p align="center">
<img src="https://github.com/farhantandia/Lightweight-DNN-Triplet-Center-Loss-Person-Reid/blob/main/results.png", width="500"><br>
</p>

*approximate parameters based on their backbone

### Benchmark References
<pre>

[29]A. Hermans, L. Beyer, and B. Leibe, “In defense of the triplet loss for person re-identification,”
[23] Y. Sun, L. Zheng, W. Deng, and S. Wang, “SVDNet for Pedestrian Retrieval,”
[24] D. Li, X. Chen, Z. Zhang, and K. Huang, “Learning deep tr-Aware features over body and latent parts for person re-identification,” 
[25] T. Guo, D. Wang, Z. Jiang, A. Men, and Y. Zhou, “Deep Network with Spatial and Channel Attention for Person Re-identification,”
[27] X. Guo, “PERSON RE-IDENTIFICATION BY DEEP LEARNING MUTI-PART INFORMATION COMPLEMENTARY 
[28] M. Jiang, Z. Li, and J. Chen, “Person Re-Identification Using Color Features and CNN Features,”

</pre>


