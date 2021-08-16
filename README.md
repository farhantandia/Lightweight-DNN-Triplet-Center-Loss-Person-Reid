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


