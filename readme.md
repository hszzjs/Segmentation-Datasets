## Segmentation Dataset

This is only a brief introduction to some semantic segmentation datasets. More detailed information and more semantic segmentation datasets will be updated in the future.

+ **PASCAL VOC(Visual Object Classes) 2012:** [[link]](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html)  [[paper]](http://host.robots.ox.ac.uk/pascal/VOC/pubs/everingham10.pdf)

	**Overview** There are 20 object classes in the dataset.
	 
	| Group | Classes |
	| :---: | :---: |
	| Person | person |
	| Animal | bird, cat, cow, dog, horse, sheep |
	| Vehicle | aeroplane, bicycle, boat, bus, car, motorbike, train |
	| Indoor | bottle, chair, dining table, potted plant, sofa, tv/monitor |
	
	Three main object recognition competitions on this dataset: classification, detection and segmentation.


+ **PASCAL-Context:** [[link]](https://www.cs.stanford.edu/~roozbeh/pascal-context/)  [[paper]](https://www.cs.toronto.edu/~urtasun/publications/mottaghi_et_al_cvpr14.pdf)
	
	**Overview** This dataset is a set of additional annotations for PASCAL VOC 2010. It goes beyond the original PASCAL semantic segmentation task by providing annotations for the whole scene. Training and validation contains 10,103 images while testing contains 9.637 images. The statistics section has a full list of 400+ labels. See **pascal-voc.txt**

+ **NYUDv2:** [[link]](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html)  [[paper]](https://cs.nyu.edu/~silberman/papers/indoor_seg_support.pdf)

	**Overview** The NYU-Depth V2 data set is comprised of video sequences from a variety of indoor scenes as recorded by both the RGB and Depth cameras from the Microsoft Kinect. 
	
	It features:

	+ 1449 densely labeled pairs of aligned RGB and depth images
	+ 464 new scenes taken from 3 cities
	+ 407,024 new unlabeled frames
Each object is labeled with a class and an instance 	+ number (cup1, cup2, cup3, etc

	The dataset has several components:

	+ Labeled: A subset of the video data accompanied by dense multi-class labels. This data has also been preprocessed to fill in missing depth labels.
	+ Raw: The raw rgb, depth and accelerometer data as provided by the Kinect.
	+ Toolbox: Useful functions for manipulating the data and labels

	
+ **SUN-RGBD:** [[link]](http://rgbd.cs.princeton.edu/)  [[paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Song_SUN_RGB-D_A_2015_CVPR_paper.pdf)

	**Overview** The dataset is captured by four different sensors and contains 10,335 RGB-D images, at a similar scale as PASCAL VOC. The whole dataset is densely annotated and includes 146,617 2D polygons and 64,595 3D bounding boxes with accurate object orientations, as well as a 3D room layout and scene category for each image. This dataset enables us to train data-hungry algorithms for scene-understanding tasks, evaluate them using meaningful 3D metrics, avoid
overfitting to a small testing set, and study cross sensor bias.

	Semantic segmentation in the 2D image domain is currently the most popular task for RGB-D scene understanding. In this task, the algorithm outputs a semantic label for each pixel in the RGB-D image. We use the standard average accuracy across object categories for evaluation

+ **Microsoft COCO:** [[link]](http://cocodataset.org/) [[paper]](https://arxiv.org/pdf/1405.0312.pdf)

	**Overview** COCO is a large-scale object detection, segmentation, and captioning dataset. COCO has several features:
	+ Object segmentation
	+ Recognition in context
	+ Superpixel stuff segmentation
	+ 330K images (>200K labeled)
	+ 1.5 million object instances
	+ 80 object categories
	+ 91 stuff categories
	+ 5 captions per image
	+ 250,000 people with keypoints

+ **Cityscape:** [[link]](https://www.cityscapes-dataset.com/)  [[paper]](https://arxiv.org/pdf/1604.01685.pdf) [[git repository]](https://github.com/mcordts/cityscapesScripts)

	**Overview** The Cityscapes Dataset focuses on semantic understanding of urban street scenes. 5,000 annotated images with fine annotations and 20,000 annotated images with coarse annotations are in the dataset. It contains 30 classes object. The class definitions details can be seen in the following:
	 

	| Group | Classes |
	| :---: | :---: |
	| flat | road · sidewalk · parking+ · rail track+ |
	| human | person* · rider* |
	| construction | building · wall · fence · guard rail+ · bridge+ · tunnel+ |
	| object | pole · pole group+ · traffic sign · traffic light |
	| nature | vegetation · terrain |
	| sky | sky |
	| void | 	ground+ · dynamic+ · static+ |

	
	
+ **CamVid:** [[link]](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/)  [[paper]](http://www0.cs.ucl.ac.uk/staff/G.Brostow/papers/Brostow_2009-PRL.pdf)

	**Overview** The Cambridge-driving Labeled Video Database(Cam Vid) is the first collection of videos with object class semantic labels, complete with metadata. The database provides ground truth labels that associate each pixel with one of 32 semantic classes. 
	
	| Group | Classes |
	| :---: | :---: |
	| Moving object | Animal · Pedestrian · Child · Rolling cart/luggage/pram · Bicyclist · Motorcycle/scooter · Car (sedan/wagon) · SUV / pickup truck · Truck / bus · Train · Misc |
	| Road | Road == drivable surface · Shoulder · Lane markings drivable · Non-Drivable |
	| Ceiling | Sky · Tunnel · Archway |
	| Fixed objects | Building · Wall · Tree · Vegetation misc. · Fence · Sidewalk · Parking block · Column/pole · Traffic cone · Bridge · Sign / symbol · Misc text · Traffic light · Other |
	
	**Labeled Images (701 so far)**
	

