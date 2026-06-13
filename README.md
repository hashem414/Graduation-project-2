README
======

Project Title: Automated Football Analytics for the Jordanian Pro League Using Computer Vision

Research Paper (Overleaf): [Paste Overleaf Link Here]

GitHub Repository: [Paste GitHub Repository Link Here]


1. OVERVIEW
===========

This folder contains the final project submission files: code notebooks, dataset files, best-case results, final video, and poster image.

For the full methodology, explanation, experiments, and analysis, please refer to the research paper linked above.


2. FOLDER STRUCTURE
===================

submission/
│
├── Code and Results/
│   ├── Code/
│   │   ├── Before_Training.ipynb
│   │   ├── Best_Results.ipynb
│   │   └── Video_Code.ipynb
│   │
│   └── Results & Video/
│       ├── Results_from_best_case/
│       └── Final_Video.zip
│
├── Our_Dataset/
│   ├── Dataset/
│   └── Our_Split_Best_Results/
│       └── Dataset.zip
│
└── Poster.jpeg


3. HOW TO RUN
=============

1. Open the Code and Results/Code folder.

2. To run the best results notebook, use the dataset stored in:

   Our_Dataset/Our_Split_Best_Results/Dataset.zip

   This dataset split is required for reproducing the best-case results.

3. Run:

   Best_Results.ipynb

   Wait until the notebook finishes running and produces the required outputs/results.

4. After the best results code is completed, run:

   Video_Code.ipynb

   This notebook uses the generated results to produce the final video/demo output.

5. The code was built using Kaggle's directory structure, so the paths are already set correctly for Kaggle. If you run the notebooks locally, some file paths may need to be changed.
