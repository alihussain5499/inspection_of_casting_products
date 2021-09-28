Project Detail¶
In the manufacturing industry, reducing processing errors in the manufacturing process is important for maximizing profits. In order to reduce processing errors, it is necessary to secure a budget for quality assurance, implement manual inspection work, and review the manufacturing process. Particularly, the inspection process is carried out by many companies, but there are problems such as uneven accuracy denpending on inspection workers and increased labor costs.
In this analysis, we will verify whether the bottleneck of "manual inspection" can be cleared by automating the inspection process by machine learning in the manufacturing process of casting products. Casting is a technique in which molten metal is poured into a mold and processed into a desired shape.
According to this article, the following are some of the defects in the casting process.

blow holes
pinholes
burr
shrinkage defects
mould material defects
pouring metal defects
metallurgical defects
About Dataset
This dataset provides image data of impellers for submersible pumps.



Submersible Pump

Impeller

The image data is labeled with ok(normal) and def(defect/anomaly) in advance. In addition, since it is necessary to illuminate the image in a stable condition when acquiring the image, the data was acquired based on a special lighting setting.

Context
This dataset is of casting manufacturing product.
Casting is a manufacturing process in which a liquid material is usually poured into a mould, which contains a hollow cavity of the desired shape, and then allowed to solidify.
Reason for collect this data is casting defects!!
Casting defect is an undesired irregularity in a metal casting process.
There are many types of defect in casting like blow holes, pinholes, burr, shrinkage defects, mould material defects, pouring metal defects, metallurgical defects, etc.
Defects are an unwanted thing in casting industry. For removing this defective product all industry have their quality inspection department. But the main problem is this inspection process is carried out manually. It is a very time-consuming process and due to human accuracy, this is not 100% accurate. This can because of the rejection of the whole order. So it creates a big loss in the company.

We decided to make the inspection process automatic and for this, we need to make deep learning classification model for this problem.

contain
These all photos are top view of submersible pump impeller(google search for better understanding).
The dataset contains total 7348 image data. These all are the size of (300*300) pixels grey-scaled images. In all images, augmentation already applied.

Also uploaded images size of 512x512 grayscale. This data set is without Augmentation. This contains 519 okfront and 781 deffront impeller images.

For capturing these images requires stable lighting, for this we made a special arrangement.

there are mainly two categories:-
1) Defective
2)Ok

making classification model we already split data for training and testing into two folders.
Both train and test folder contains deffront and okfront subfolders.

train:- deffront have 3758 and okfront have 2875 images
test:- deffront have:- deffront have 453 and ok_front have 262 images

Acknowledgements
We wouldn't be here without the help of PILOT TECHNOCAST, Shapar, Rajkot. we have to thank them for constant support and allowing us to work for this problem.
