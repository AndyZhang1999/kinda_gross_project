# Skin-Hair-Removal-Based-On-Digital-Image-Processing-replication
A hair removal method (I'm serious...), replicated with the paper COMPARATIVE ANALYSIS OF AUTOMATIC SKIN LESION SEGMENTATION WITH TWO DIFFERENT IMPLEMENTATIONS as a reference.

Please look at the comments (chin version though) in the code file for how to use the code.

Hair_Removal.py is a reproduction of the hair removal method in the Method 1 preprocessing step in the paper.

Hair_Removal_with_groundtruthimg.py is based on Hair_Removal.py and uses ground truth to improve image processing quality.

Hair_Removal_with_groundtruthimg_batch_processing.py is the batch processing version of Hair_Removal_with_groundtruthimg.py and can be used to batch process multiple images in a folder

The partial processing effect of Hair_Removal_with_groundtruthimg.py is as follows:

![](https://i.loli.net/2020/12/10/5F1OPt7QElwvXKM.jpg)

![](https://i.loli.net/2020/12/10/RmJa5sdbLenMBFX.jpg)

![](https://i.loli.net/2020/12/10/j2O934xYUblsEpg.jpg)

Comparison of the results of Hair_Removal_with_groundtruthimg.py and Hair_Removal.py. The image on the left is the processing result of Hair_Removal.py, and the image on the right is the processing result of Hair_Removal_with_groundtruthimg.py.

![](https://i.loli.net/2020/12/10/k6gHBP4GDlfCiS5.png)

![](https://i.loli.net/2020/12/10/FKICciTu83HN1EQ.png)

![](https://i.loli.net/2020/12/10/PxHQt7TbEFkZMon.png)

Ref:
Hasan, M.K., Alyafi, B., & Tushar, F.I. (2019). Comparative Analysis of Automatic Skin Lesion Segmentation with Two Different Implementations. ArXiv, abs/1904.03075.
