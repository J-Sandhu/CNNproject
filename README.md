## CNNproject
Convolutional neural network project made in Python with PyTorch and NumPy.
After long deliberation with professors and peers, the outline of the project has been decided.
The project will be focused on image segmentation. The model will draw data from thepie.com/live, preprocess individual frames and output number of persons.
The project could have other outputs too, intermediate steps, debugging, etc.
# Milestone Planning
1. Data scraping. (Work with library image sets until complete)
2. Preprocessing.
  a. Spatial Transform (adjust for camera lens distortion)
  b. Contrast Enhancement (separate foreground and background)
  c. Edge Detection (Find derivatives to better inform downstream task, Tentative)
  d. Morphological Transform (Stopping nearby features from being merged)
  e. Seeding/Hole filling (getting solid blocks)
  f. Motion detection (Comparing contiguous frames)
3. training the model (strategy undecided: unsupervised/supervised/etc.)
