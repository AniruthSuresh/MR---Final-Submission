\documentclass{article}
\usepackage[a4paper,margin=1in]{geometry}
\usepackage{hyperref}
\usepackage{enumitem}

\begin{document}

\title{Project: Final Submission}
\author{}
\date{}
\maketitle

\section*{Overview}
This repository contains the final submission of our projects, including both reports and code implementations. The projects are as follows:

\begin{enumerate}
    \item \textbf{Direct Sparse Odometry (DSO) and DM-VIO:} 
    - Comparative analysis of pose estimation techniques.
    - Implementation and benchmarking on real-world datasets.

    \item \textbf{Semi-Global Block Matching (SGBM) and 3D Scene Reconstruction:}
    - Implementation of SGBM for stereo image disparity computation.
    - Transformation of disparity maps into 3D point clouds for scene reconstruction.
\end{enumerate}

\section*{Datasets}
For the SGBM implementation, we utilize the KITTI stereo dataset. You can download the dataset from the following link:
\begin{itemize}[label=--]
    \item \href{https://www.cvlibs.net/datasets/kitti/eval_stereo_flow.php?benchmark=stereo}{KITTI Stereo Dataset}
\end{itemize}

