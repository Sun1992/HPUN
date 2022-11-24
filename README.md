# HPUN (Hybrid-Pixel-Unshuffle-Network)
This repo is the official results of the paper:
Hybrid Pixel-Unshuffled Network for Lightweight Image Super-Resolution

Authors: Bin Sun, Yulun Zhang, Songyao Jiang, Yun Fu

Contact Email: sun.bi@northeastern.edu

The preprinted version is: https://arxiv.org/abs/2203.08921

If you think the work is interesting to follow, please cite the paper with:
```
@article{sun2022hybrid,
  title={Hybrid Pixel-Unshuffled Network for Lightweight Image Super-Resolution},
  author={Sun, Bin and Zhang, Yulun and Jiang, Songyao and Fu, Yun},
  journal={arXiv preprint arXiv:2203.08921},
  year={2022}
}
```
This repo is the test code revised from https://github.com/yulunzhang/RCAN/tree/master/RCAN_TestCode.

Since we have licensed the patent, we cannot release the training code and pretrained model. If you are interested in the technology, please visit ainnovationlabs.com and contact them.

The results are on google drive:
https://drive.google.com/file/d/1JTDdUSKdbWm3GpE8RBq590zdRWxAyixw/view?usp=sharing

Please create a dir SR/BI/ and put the results to SR/BI/


The GT HR images are on google drive:
https://drive.google.com/file/d/1F4HGfTh2cnzPiBjRAJloqHPI7fz1mHqA/view?usp=sharing

Please put the results to the directory and upzip the file

We have sucessfully deployed model on iPhone Xs Max. The real-time demo is shown below:


https://user-images.githubusercontent.com/15020820/203320884-a6756cc4-492e-445b-aa63-79e4ee6cfd21.MP4

The quantitative results are:

<img width="824" alt="image" src="https://user-images.githubusercontent.com/15020820/203330426-2373bc06-013b-4cdf-bb18-4c9bcc4569cc.png">

Besides, you are welcome to explore the phenomenon found in the paper with us. The phenomenon is about the relationship between PSNR and the NME of shallow features and deep features,  which is shown below:

<img width="712" alt="image" src="https://user-images.githubusercontent.com/15020820/203328068-825e4166-6324-4da6-a18a-554539bf91c7.png">

<img width="740" alt="image" src="https://user-images.githubusercontent.com/15020820/203327950-38c34b13-e252-415d-b752-e37bc3c0a7bc.png">


