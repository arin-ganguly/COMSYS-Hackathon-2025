## Task A: Gender Classification (Binary Classification)
In this task, participants must build a binary classification model to distinguish between male and female faces.
-	Dataset Structure:
o	train/: Contains two subfolders — male/ and female/ with respective images.
o	val/: Contains similarly structured validation data.
•	Objective: Train a model to accurately classify the gender of a face image.
---
## Task B: Face Recognition (Multi-Class Classification)
This task challenges participants to develop a multi-class face recognition system with an added twist of matching against distorted images.
- Dataset Structure:
Each folder represents a unique individual and contains one or more face images.
-	A distorted/ folder contains altered versions of face images.
- Objective:
- Match an input face image to its corresponding person folder.
- If a test image (or its distorted variant) matches any image in the same folder, it is considered a match (label = 1).
-	If it matches an image from a different folder, it's a non-match (label = 0).
