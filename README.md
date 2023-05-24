# rooms-detection

**Dataset**

The data contains images concerning different indoor scenes from rooms and locations commonly present in a standard family home. The task is to predict the type of room/scene present in the image. Indoor scene recognition is a challenging problem since some indoor scenes can be well defined by global spatial and structural proper- ties, while others are better characterized by the objects included in the space. The dataset is a subset of a larger dataset for indoor scene recognition. More information is available here:

http://web.mit.edu/torralba/www/indoor.html.

The images are divided into train, validation, and test folders, each containing the folders related to the type of the room in the image (i.e. the categories of the target variable): bathroom, bedroom, children_room, closet, corridor, dining_room, garage, kitchen, living_room, stairs. The number of images available for each scene is variable and it ranges from 52 to 367 in the training set, with validation and test sets being roughly half the size.

**Task**

The task is to build a predictive model to predict the type of indoor scene from the image data. 4 CNN models are used with different setting and configurations. 

