# Behavioural-Mouse-Dataset

The Mouse Behavioral Dataset is a comprehensive resource designed to facilitate the classification of various behavioral patterns exhibited by mice within a vivarium environment. This dataset has over 1 milion labeled images offers a meticulously curated collection of behavioral observations, encompassing individual actions as well as social interactions among mice.The primary source of data for the Mouse Behavioral Dataset is video recordings captured within our vivarium environment. These recordings, spanning 35 minutes of active daily footage, are carefully selected to capture a broad spectrum of behavioral observations among mice.

# Annotation Process
Behavioral annotations are applied to each frame of the video recordings using the BORIS software, a specialized tool for behavioral observation and annotation. These annotations categorize behaviors into distinct classes, including individual actions such as resting, rearing up, running, self-grooming, and exploration, as well as social interactions such as fighting, grooming others, and close investigation.

# Data Processing
Video frames are processed using the OpenCV library to extract individual frames, facilitating subsequent annotation and analysis. Relevant data structures, including unique identifiers, bounding boxes, and keypoints, are loaded from accompanying data files in NPY format, leveraging the capabilities of the NumPy package for efficient data manipulation.

# Annotation Integration
Mice within each frame are identified based on their track information, and bounding boxes are adjusted accordingly to ensure precise localization. Regions of interest (ROIs) corresponding to each mouse are extracted from the frames based on the adjusted bounding boxes, providing focused areas for behavioral analysis. Keypoints associated with each mouse are mapped onto the ROIs using a color-coded scheme to denote key anatomical landmarks.

# Download
You can download the dataset using this link:
https://ulavaldti-my.sharepoint.com/:f:/r/personal/msmon3_ulaval_ca/Documents/Darsi/PhD/Smart%20Vivarium%20-%20Vincent/behaviour%20classifier/dataset/Behavioural%20Mouse%20Dataset?csf=1&web=1&e=grK84E

Or you can ask for it using these emails:
mohammad-sadegh.monfared.1@gmail.com
msadeghmonfared@gmail.com 
