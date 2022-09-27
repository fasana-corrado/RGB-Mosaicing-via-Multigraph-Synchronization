# RGB Image Mosaicing via Multi-graph synchronization

## Abstract:
Image mosaicing is an effective means of constructing a single seamless image by aligning multiple partially overlapped images.
Over the years several different approaches have been proposed to solve the various steps of the mosaicing pipeline such as alignment and compositing.
Our paper aims to propose a solution for Global Homography Estimation, a fundamental step of image alignment, based on multi-graph synchronization.
Furthermore, an experimental framework is set up to compare our approach with others present in the literature. The results are evaluated both qualitatively and quantitatively, showing the overall superiority of two variants of multi-graph synchronization w.r.t. other Global Homography Estimation techniques.

## Instructions:
1) Install the requirements via the command "pip install -r requirements.txt".
2) Run Main.ipynb to reproduce a single experiment. It is possible to choose the dataset and other parameters as specified in the comments.
3) Run ExperimentalResults.ipynb to run multiple experiments using the same dataset and settings.
4) Run Benchmark.ipynb to visualize statistics about the conducted experiments.

## Intermediate results
Intermediate results can be visualized and saved setting "verbose = True", "save_output = True" and "save_images = True".

## Dataset acquisition
If a new dataset is to be acquired, it is necessary to ensure that images are taken rotating the camera around its center.

