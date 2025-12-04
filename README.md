# Texture Defect Detection — Final Deliverables

Contents:

-   `Texture_Defect_Detection_final.ipynb`: Jupyter notebook implementing a simple defect detection pipeline.
-   `detection_outputs/`: produced predictions (PNG files named `<image>_pred.png`) after running the notebook.
-   `texture_video_defects.avi`: video produced by the notebook when `texture_video.avi` is present.
-   `presentation.md`: a short slide template describing the method and results.

How to run:

1. Place the folder `texture test images` and `texture_video.avi` in the same folder as the notebook.
2. Open `Texture_Defect_Detection_final.ipynb` in JupyterLab / VS Code and run the cells sequentially.
3. Outputs:
    - PNG prediction images will be saved into `detection_outputs/` with `_pred.png` suffix.
    - The video result is saved as `texture_video_defects.avi` (if `texture_video.avi` exists).

Notes:

-   The notebook enforces output format: non-defect pixels = 255, defect pixels = 0.
-   If packages are missing, uncomment the pip install cell at the top of the notebook.
-   If ground-truth files are named non-standardly, adjust pairing logic in the notebook (cell that builds `pairs`).

Contact:

-   If you want me to also produce a PPTX file, I can generate a simple `presentation.pptx` next.
