# VPULab-CityFlow-ReID-Evaluation-Framework

### Paper

Python evaluation framework described in our paper (https://link.springer.com/article/10.1007/s11042-023-14511-0)
### Setup

*Clone repository*
```
$ git clone https://github.com/Paulamde/VPULab-CityFlow-ReID-Evaluation-Framework.git
```
*Anaconda environment*
To create and setup the Anaconda Enviroment, open a terminal window in the repository folder and type:

```
$ conda env create -f envEvCity.yml
$ conda activate EvCity
```
### Running
*Dataset*

This github provides the Ground truth annotations of the CityFlow-ReID test set. The dataset can be downloaded at https://www.aicitychallenge.org/2020-data-and-evaluation/


*Run evaluation code*
To run evaluation code you need your track2.txt file obtained with your ReID system. To test the code, we provide a sample track2.txt

```
$ python Evaluation_CityFlow.py  
```



# Citation

If you find this code and work useful, please consider citing:
```
@article{moral2023enhancing,
  title={Enhancing vehicle re-identification via synthetic training datasets and re-ranking based on video-clips information},
  author={Moral, Paula and Garc{\'\i}a-Mart{\'\i}n, {\'A}lvaro and Mart{\'\i}nez, Jos{\'e} M and Besc{\'o}s, Jes{\'u}s},
  journal={Multimedia Tools and Applications},
  pages={1--21},
  year={2023},
  publisher={Springer}
}
```
