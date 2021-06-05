###CSRNet-python3
This is the PyTorch version repo for CSRNet: Dilated Convolutional Neural Networks for Understanding the Highly Congested Scenes in CVPR 2018, which delivered a state-of-the-art, straightforward and end-to-end architecture for crowd counting tasks.

###Prerequisites
You can use Anaconda as the environment with the following requirments
Python: 3.8
Pytorch: 1.7
CUDA: 10.1

###Ground Truth
Please follow the make_dataset.ipynb to generate the ground truth. It shall take some time to generate the dynamic ground truth. Or you can  generate your own json file.(such as train.json, val.json)


###Training Process
Try python train.py train.json val.json 0 0 to start training process.

###Validation
Follow the val.ipynb to try the validation. You can try to modify the notebook and see the output of each image.

###Results
ShanghaiA MAE: 66.4 GoogleDrive(https://drive.google.com/file/d/1Z-atzS5Y2pOd-nEWqZRVBDMYJDreGWHH/view) 
ShanghaiB MAE: 10.6 Google Drive(https://drive.google.com/file/d/1zKn6YlLW3Z9ocgPbP99oz7r2nC7_TBXK/view)


###References
@inproceedings{li2018csrnet,
  title={CSRNet: Dilated convolutional neural networks for understanding the highly congested scenes},
  author={Li, Yuhong and Zhang, Xiaofan and Chen, Deming},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={1091--1100},
  year={2018}
}

