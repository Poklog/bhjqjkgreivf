# Presentation — Texture Defect Detection

Slide 1 - Title

-   Title: Texture Defect Detection
-   Author: [Your Name]
-   Course / Semester

Slide 2 - Problem

-   Briefly describe the dataset: two test images + ground truth, one video with defects (line & region defects).
-   Output expected: PNGs where non-defect=255 and defect=0.

Slide 3 - Method

-   Convert to grayscale
-   Gaussian blur to reduce noise
-   Otsu thresholding to separate regions
-   Morphological clean-up (remove small objects/holes)
-   Map defects to 0, non-defects to 255

Slide 4 - Metrics

-   Show Accuracy, Precision, Recall per test image (values produced by notebook)
-   Brief interpretation: strengths/weaknesses of chosen method

Slide 5 - Results

-   Insert example input, predicted mask, and ground truth images
-   Mention video output: `texture_video_defects.avi` with red contour overlays

Slide 6 - Conclusions

-   Simplicity vs performance trade-offs
-   Possible improvements: adaptive thresholding, background modeling, texture filters (Gabor), ML approaches

Slide 7 - How to run

-   Short run instructions (see README)

-- End --
