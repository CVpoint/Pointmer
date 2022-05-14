# Dependencies

- Ubuntu: 18.04 or higher
- Putorch: 1.8.1 
- CUDA: 11.0

## Dataset

- download S3DIS dataset from <a href="https://drive.google.com/uc?export=download&id=1KUxWagmEWnvMhEb4FRwq2Mj0aa3U3xUf" title="超链接title">s3dis</a>

- mkdir -p dataset

  > ln -s path_to_s3dis_dataset dataset

 - download ModelNetyo from <a href ="https://shapenet.cs.stanford.edu/media/modelnet40_normal_resampled.zip"  tittle="超链接title">ModelNet40</a> and save in dataset

## Classification

make sure the program in your path correctly and run：

~~~
cd tools
python train_class.py
~~~

## Segmentation

make sure the program in your path correctly and run：

~~~
python s3dis.py
cd tools
python train_seg.py
~~~



