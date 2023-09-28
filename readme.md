## Visual Behavior项目demo
### PnP Transformer
目的：设计一个Transformer模型来解决SLAM中的PnP问题
#### 训练集表现
超过传统的`RANSACEPnP`算法
[训练集效果(https://github.com/GUOkekkk/vb_demo/blob/main/assets/pnp_transformer_train.png)
#### 测试集表现
损失函数不收敛

### BEV VO
提升前端VO特征提取的性能
#### ORB Feature
特征点太中心化，容易检测噪点为特征点
#### ORB SLAM feature
特征点分布均匀，但是鲁棒性不强，容易检测噪点为特征点
#### SuperPoint+LightGlue
稳定
