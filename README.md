# PointNet-Keras
PointNet keras implementation

Original tensorflow implementation:[pointnet](https://github.com/charlesq34/pointnet)

A Keras port of PointNet:[pointnet-keras](https://github.com/garyli1019/pointnet-keras)

## 3D Classification

### Prepear Data

Download the aligned dataset [ModelNet40](https://shapenet.cs.stanford.edu/media/modelnet40_ply_hdf5_2048.zip), Put all traning h5 files under './ModelNet40/train/' folder, all testing h5 files under './ModelNet40/test/' folder, then run prepearData.py.

### Training

    python train_cls.py
    
### Results

Best val acc: 88.83%

Train and val acc during training.

![acc](https://github.com/TianzhongSong/PointNet-Keras/blob/master/results/model_accuracy.png)

Train and val loss during training.

![loss](https://github.com/TianzhongSong/PointNet-Keras/blob/master/results/model_loss.png)


## 3D Segmentation

Todo


## Reference

[pointnet-keras](https://github.com/garyli1019/pointnet-keras)
