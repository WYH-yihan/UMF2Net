# UMF2Net

This repository provides the implementation of UMF2Net for hyperspectral anomaly detection.

## Overview

In hyperspectral image (HSI) anomaly detection (AD) methods, detecting small targets or
anomalies remains challenging. This difficulty arises because targets or anomalies may
vary significantly in size, shape, and texture, causing them to be obscured by larger-scale
background features. To address the above issue, this paper proposes an unsupervised
multi-scale feature fusion network (UMF2Net) for HSI-AD. Firstly, central difference convo-
lution analyzes the image at multiple scales to capture fine-to-coarse details and structural
information. Additionally, three-dimensional (3D) convolution is employed to generate
feature weights for the multi-scale features, assigning different weights to features with
different contributions so that the model dynamically emphasizes features that have a
greater impact on the AD results. Finally, by using the two proposed multi-scale feature
fusion modules, the model effectively integrates features at different scales, thereby en-
hancing its ability to detect anomalies of varying sizes. Compared with several classical
HSI-AD algorithms on real hyperspectral datasets from four scenarios, UMF2Net achieved
competitive detection results, verifying the effectiveness of our algorithm. 

## Dataset

The experiments are conducted on commonly used hyperspectral anomaly detection datasets.

## Code

The source code will be released after the paper is officially published.


