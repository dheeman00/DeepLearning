•	Purpose:
	Contains the test images — grayscale handwritten digits.
•	Format:
	Binary file with 10,000 images, each of size 28×28 pixels.
	•	Structure:
	•	Header (16 bytes):
	•	0–3   → Magic number (always 2051 for image files)
	•	4–7   → Number of images (10,000)
	•	8–11  → Number of rows (28)
	•	12–15 → Number of columns (28)
	•	Data:
	•	Each pixel stored as 1 byte (0–255), arranged row-wise.
	•	Each image uses 784 bytes (28 × 28), uncompressed.
