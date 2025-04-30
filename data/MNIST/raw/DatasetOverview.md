File: t10k-images-idx3-ubyte
	•	Purpose: Contains the test images (handwritten digits).
	•	Format: Binary file storing 10,000 grayscale images, each of size 28×28 pixels.
	•	Structure:
	•	Header (16 bytes total):
	  •	[0–3]: Magic number (always 2051 for image files)
	  •	[4–7]: Number of images (10,000)
	  •	[8–11]: Number of rows (28)
	  •	[12–15]: Number of columns (28)
	•	Data:
	  •	Each pixel is stored as a single byte (0–255), row-wise for each image.
	  •	Each image occupies 784 bytes (28×28), uncompressed.

  File: t10k-labels-idx1-ubyte
	•	Purpose: Contains the labels for the 10,000 test images.
	•	Format: Binary file storing integer class labels (0–9).
	•	Structure:
	•	Header (8 bytes total):
	  •	[0–3]: Magic number (2049 for label files)
	  •	[4–7]: Number of labels (10,000)
	•	Data:
	  •	1 byte per label (value from 0 to 9), matching the corresponding image.

 
