# Composite Unsupervised Efficiency Score: An Objective Multi-Criteria Framework for Feature Matching Algorithm Evaluation in UAV Photogrammetry

Author: A.Abbas ELMAS, Barış ATA

This repository provides feature matching visualization results and interactive analytical dashboards accompanying the study.

## Research Summary

- 784 algorithm combinations evaluated across 5 diverse datasets spanning controlled synthetic, standardized benchmark, and real-world operational scenarios
- Composite Unsupervised Efficiency Score (CUES) integrates four unsupervised weighting approaches: Entropy, CRITIC, PCA, and Variance
- Cross-dataset consistency validated with 0.805 average Spearman rank correlation across 250 mutually valid combinations
- Methodological stability: $\alpha$ parameter stability avg $\rho = 0.9845$, weight aggregation stability avg $\rho = 0.9993$
- Best unified cross-dataset performer: ORB-BEBLID-HAM-BF (average 0.7517)
- Best overall feature detector: AKAZE (average 0.5455)
- Best overall feature descriptor: SIFT (average 0.6147)
- Best peak performer (controlled synthetic): ORB-ORB-HAM-BF (0.8538)
- Best UAV: ORB-BEBLID-HAM-BF (0.7249)
- Most stable high performer: AKAZE-SIFT-L2-BF (CoV: 0.0801)

## Interactive Dashboards

Access comprehensive analysis dashboards:

| Dataset | Main | Efficiency | Timing | Correlation | Heatmap | Violin |
|---------|------|------------|--------|-------------|---------|--------|
| Synthetic | [Analysis](/html/synthetic/synthetic.html) | [Efficiency](/html/synthetic/synthetic_Efficiency.html)    | [Timing](/html/synthetic/syntheticTiming.html) | [Correlation](/html/synthetic/synthetic_Correlation.html)  | [Heatmap](/html/synthetic/synthetic_Heatmap.html)  | [Violin](/html/synthetic/synthetic_Violin.html)    |
| Oxford    | [Analysis](/html/oxford/oxford.html)       | [Efficiency](/html/oxford/oxford_Efficiency.html)          | [Timing](/html/oxford/oxfordTiming.html)       | [Correlation](/html/oxford/oxford_Correlation.html)        | [Heatmap](/html/oxford/oxford_Heatmap.html)        | [Violin](/html/oxford/oxford_Violin.html)          |
| AirSim    | [Analysis](/html/airsim/airsim.html)       | [Efficiency](/html/airsim/airsim_Efficiency.html)          | [Timing](/html/airsim/airsimTiming.html)       | [Correlation](/html/airsim/airsim_Correlation.html)        | [Heatmap](/html/airsim/airsim_Heatmap.html)        | [Violin](/html/airsim/airsim_Violin.html)          |
| UAV       | [Analysis](/html/uav/uav.html)             | [Efficiency](/html/uav/uav_Efficiency.html)                | [Timing](/html/uav/uavTiming.html)             | [Correlation](/html/uav/uav_Correlation.html)              | [Heatmap](/html/uav/uav_Heatmap.html)              | [Violin](/html/uav/uav_Violin.html)                |
| Drone     | [Analysis](/html/drone/drone.html)         | [Efficiency](/html/drone/drone_Efficiency.html)            | [Timing](/html/drone/droneTiming.html)         | [Correlation](/html/drone/drone_Correlation.html)          | [Heatmap](/html/drone/drone_Heatmap.html)          | [Violin](/html/drone/drone_Violin.html)            |

## Feature Matching Visualizations

Interactive JPG and HTML visualizations for top-performing algorithm combinations across 784 evaluated configurations. Each visualization includes match quality metrics, timing statistics, and toggleable information overlays.

### Top 5 Algorithm Combinations per Dataset

| Dataset | Rank | Algorithm Combination | CUES | Static | Interactive |
|---------|------|-----------------------|------|--------|-------------|
| **Synthetic** | 1 | ORB-ORB-HAM-BF | 0.8538 | [JPG](/draws/rot/woman_4_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| | 2 | ORB-ORB-HAM-FLANN | 0.8335 | [JPG](/draws/rot/woman_4_2ORB_2ORB_ham_flann_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_flann.html) |
| | 3 | SIFT-BEBLID-HAM-BF | 0.8229 | [JPG](/draws/rot/woman_4_0SIFT_11BEBLID_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_0SIFT_11BEBLID_ham_bf.html) |
| | 4 | SIFT-BOOST-HAM-BF | 0.8190 | [JPG](/draws/rot/woman_4_0SIFT_13BOOST_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_0SIFT_13BOOST_ham_bf.html) |
| | 5 | ORB-TEBLID-HAM-BF | 0.8188 | [JPG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html) |
| **Oxford** | 1 | ORB-BEBLID-HAM-BF | 0.6264 | [JPG](/draws/bark/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_11BEBLID_ham_bf.html) |
| | 2 | ORB-TEBLID-HAM-BF | 0.6202 | [JPG](/draws/bark/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_12TEBLID_ham_bf.html) |
| | 3 | ORB-ORB-HAM-BF | 0.6038 | [JPG](/draws/bark/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_2ORB_ham_bf.html) |
| | 4 | ORB-TEBLID-HAM-FLANN | 0.5902 | [JPG](/draws/bark/2_2ORB_12TEBLID_ham_flann_.jpg) | [HTML](/draws/bark/2_2ORB_12TEBLID_ham_flann.html) |
| | 5 | ORB-BEBLID-HAM-FLANN | 0.5868 | [JPG](/draws/bark/2_2ORB_11BEBLID_ham_flann_.jpg) | [HTML](/draws/bark/2_2ORB_11BEBLID_ham_flann.html) |
| **AirSim** | 1 | ORB-BEBLID-HAM-BF | 0.8064 | [JPG](/draws/airsim/2_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_bf.html) |
| | 2 | ORB-TEBLID-HAM-BF | 0.7968 | [JPG](/draws/airsim/2_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_bf.html) |
| | 3 | MSD-BEBLID-HAM-BF | 0.7547 | [JPG](/draws/airsim/2_12MSD_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_12MSD_11BEBLID_ham_bf.html) |
| | 4 | KAZE-BEBLID-HAM-BF | 0.7528 | [JPG](/draws/airsim/2_4KAZE_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_4KAZE_11BEBLID_ham_bf.html) |
| | 5 | ORB-BEBLID-HAM-FLANN | 0.7458 | [JPG](/draws/airsim/2_2ORB_11BEBLID_ham_flann.jpg) | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_flann.html) |
| **UAV** | 1 | ORB-BEBLID-HAM-BF | 0.7249 | [JPG](/draws/uav/8_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_2ORB_11BEBLID_ham_bf.html) |
| | 2 | AGAST-BEBLID-HAM-BF | 0.7212 | [JPG](/draws/uav/8_7AgastFeatureDetector_11BEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_11BEBLID_ham_bf.html) |
| | 3 | ORB-TEBLID-HAM-BF | 0.7123 | [JPG](/draws/uav/8_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_2ORB_12TEBLID_ham_bf.html) |
| | 4 | AGAST-TEBLID-HAM-BF | 0.7118 | [JPG](/draws/uav/8_7AgastFeatureDetector_12TEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_12TEBLID_ham_bf.html) |
| | 5 | AKAZE-DAISY-L2-FLANN | 0.6949 | [JPG](/draws/uav/8_1AKAZE_5DAISY_l2_flann.jpg) | [HTML](/draws/uav/8_1AKAZE_5DAISY_l2_flann.html) |
| **Drone** | 1 | ORB-ORB-HAM-BF | 0.8028 | [JPG](/draws/drone/17_2ORB_2ORB_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_2ORB_ham_bf.html) |
| | 2 | ORB-BEBLID-HAM-BF | 0.8008 | [JPG](/draws/drone/17_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_bf.html) |
| | 3 | ORB-TEBLID-HAM-BF | 0.7786 | [JPG](/draws/drone/17_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_12TEBLID_ham_bf.html) |
| | 4 | ORB-ORB-HAM-FLANN | 0.7611 | [JPG](/draws/drone/17_2ORB_2ORB_ham_flann.jpg) | [HTML](/draws/drone/17_2ORB_2ORB_ham_flann.html) |
| | 5 | ORB-DAISY-L2-FLANN | 0.7600 | [JPG](/draws/drone/17_2ORB_5DAISY_l2_flann.jpg) | [HTML](/draws/drone/17_2ORB_5DAISY_l2_flann.html) |

### Drone Dataset Visualizations

| Algorithm Combination | CUES | Static | Interactive |
|-----------------------|------|--------|-------------|
| ORB-ORB-HAM-BF | 0.8028 | [JPG](/draws/drone/17_2ORB_2ORB_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_2ORB_ham_bf.html) |
| ORB-BEBLID-HAM-BF | 0.8008 | [JPG](/draws/drone/17_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | 0.7786 | [JPG](/draws/drone/17_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-FLANN | 0.7611 | [JPG](/draws/drone/17_2ORB_2ORB_ham_flann.jpg) | [HTML](/draws/drone/17_2ORB_2ORB_ham_flann.html) |
| ORB-DAISY-L2-FLANN | 0.7600 | [JPG](/draws/drone/17_2ORB_5DAISY_l2_flann.jpg) | [HTML](/draws/drone/17_2ORB_5DAISY_l2_flann.html) |
| ORB-BEBLID-HAM-FLANN | 0.7511 | [JPG](/draws/drone/17_2ORB_11BEBLID_ham_flann.jpg) | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_flann.html) |
| ORB-DAISY-L2-BF | 0.7494 | [JPG](/draws/drone/17_2ORB_5DAISY_l2_bf.jpg) | [HTML](/draws/drone/17_2ORB_5DAISY_l2_bf.html) |
| GFTT-DAISY-L2-FLANN | 0.7473 | [JPG](/draws/drone/17_8GFTTDetector_5DAISY_l2_flann.jpg) | [HTML](/draws/drone/17_8GFTTDetector_5DAISY_l2_flann.html) |
| ORB-TEBLID-HAM-FLANN | 0.7403 | [JPG](/draws/drone/17_2ORB_12TEBLID_ham_flann.jpg) | [HTML](/draws/drone/17_2ORB_12TEBLID_ham_flann.html) |
| GFTT-DAISY-L2-BF | 0.7363 | [JPG](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.html) |

### UAV Dataset Visualizations

| Algorithm Combination | CUES | Static | Interactive |
|-----------------------|------|--------|-------------|
| ORB-BEBLID-HAM-BF | 0.7249 | [JPG](/draws/uav/8_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_2ORB_11BEBLID_ham_bf.html) |
| AGAST-BEBLID-HAM-BF | 0.7212 | [JPG](/draws/uav/8_7AgastFeatureDetector_11BEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | 0.7123 | [JPG](/draws/uav/8_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_2ORB_12TEBLID_ham_bf.html) |
| AGAST-TEBLID-HAM-BF | 0.7118 | [JPG](/draws/uav/8_7AgastFeatureDetector_12TEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_12TEBLID_ham_bf.html) |
| AKAZE-DAISY-L2-FLANN | 0.6949 | [JPG](/draws/uav/8_1AKAZE_5DAISY_l2_flann.jpg) | [HTML](/draws/uav/8_1AKAZE_5DAISY_l2_flann.html) |
| AGAST-VGG-L2-BF | 0.6917 | [JPG](/draws/uav/8_7AgastFeatureDetector_10VGG_l2_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_10VGG_l2_bf.html) |
| AGAST-SIFT-L2-BF | 0.6910 | [JPG](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.html) |
| MSD-BEBLID-HAM-BF | 0.6905 | [JPG](/draws/uav/8_12MSD_11BEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_12MSD_11BEBLID_ham_bf.html) |
| FAST-BEBLID-HAM-BF | 0.6885 | [JPG](/draws/uav/8_5FastFeatureDetector_11BEBLID_ham_bf.jpg) | [HTML](/draws/uav/8_5FastFeatureDetector_11BEBLID_ham_bf.html) |
| GFTT-DAISY-L2-BF | 0.6880 | [JPG](/draws/uav/8_8GFTTDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_8GFTTDetector_5DAISY_l2_bf.html) |

### AirSim Dataset Visualizations

| Algorithm Combination | CUES | Static | Interactive |
|-----------------------|------|--------|-------------|
| ORB-BEBLID-HAM-BF | 0.8064 | [JPG](/draws/airsim/2_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | 0.7968 | [JPG](/draws/airsim/2_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_bf.html) |
| MSD-BEBLID-HAM-BF | 0.7547 | [JPG](/draws/airsim/2_12MSD_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_12MSD_11BEBLID_ham_bf.html) |
| KAZE-BEBLID-HAM-BF | 0.7528 | [JPG](/draws/airsim/2_4KAZE_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_4KAZE_11BEBLID_ham_bf.html) |
| ORB-BEBLID-HAM-FLANN | 0.7458 | [JPG](/draws/airsim/2_2ORB_11BEBLID_ham_flann.jpg) | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_flann.html) |
| MSD-TEBLID-HAM-BF | 0.7451 | [JPG](/draws/airsim/2_12MSD_12TEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_12MSD_12TEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-FLANN | 0.7450 | [JPG](/draws/airsim/2_2ORB_12TEBLID_ham_flann.jpg) | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_flann.html) |
| KAZE-TEBLID-HAM-BF | 0.7399 | [JPG](/draws/airsim/2_4KAZE_12TEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_4KAZE_12TEBLID_ham_bf.html) |
| KAZE-SIFT-L2-FLANN | 0.7375 | [JPG](/draws/airsim/2_4KAZE_0SIFT_l2_flann.jpg) | [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_flann.html) |
| KAZE-SIFT-L2-BF | 0.7343 | [JPG](/draws/airsim/2_4KAZE_0SIFT_l2_bf.jpg) | [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_bf.html) |

### Synthetic Dataset Visualizations (Rotation)

| Algorithm Combination | CUES | Static | Interactive |
|-----------------------|------|--------|-------------|
| ORB-ORB-HAM-BF | 0.8538 | [JPG](/draws/rot/woman_4_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| ORB-ORB-HAM-FLANN | 0.8335 | [JPG](/draws/rot/woman_4_2ORB_2ORB_ham_flann_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_flann.html) |
| SIFT-BEBLID-HAM-BF | 0.8229 | [JPG](/draws/rot/woman_4_0SIFT_11BEBLID_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_0SIFT_11BEBLID_ham_bf.html) |
| SIFT-BOOST-HAM-BF | 0.8190 | [JPG](/draws/rot/woman_4_0SIFT_13BOOST_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_0SIFT_13BOOST_ham_bf.html) |
| ORB-TEBLID-HAM-BF | 0.8188 | [JPG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html) |
| SIFT-TEBLID-HAM-BF | 0.8186 | [JPG](/draws/rot/woman_4_0SIFT_12TEBLID_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_0SIFT_12TEBLID_ham_bf.html) |
| ORB-BOOST-HAM-BF | 0.8157 | [JPG](/draws/rot/woman_4_2ORB_13BOOST_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.html) |
| STAR-BRISK-HAM-BF | 0.8096 | [JPG](/draws/rot/woman_4_10STAR_3BRISK_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.html) |
| ORB-BEBLID-HAM-BF | 0.8002 | [JPG](/draws/rot/woman_4_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_11BEBLID_ham_bf.html) |
| STAR-BRISK-HAM-FLANN | 0.7973 | [JPG](/draws/rot/woman_4_10STAR_3BRISK_ham_flann_.jpg) | [HTML](/draws/rot/woman_4_10STAR_3BRISK_ham_flann.html) |

### Oxford Affine Dataset Visualizations

Representative visualizations for top Oxford performers across 8 scenarios (bark, bikes, boat, graf, leuven, trees, ubc, wall).

#### Bark (Viewpoint Change)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/bark/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/bark/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/bark/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_2ORB_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/bark/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/bark/2_1AKAZE_0SIFT_l2_bf.html) |
| AGAST-BEBLID-HAM-BF | [JPG](/draws/bark/2_7AgastFeatureDetector_11BEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_7AgastFeatureDetector_11BEBLID_ham_bf.html) |
| AKAZE-AKAZE-HAM-BF | [JPG](/draws/bark/2_1AKAZE_1AKAZE_ham_bf_.jpg) | [HTML](/draws/bark/2_1AKAZE_1AKAZE_ham_bf.html) |

#### Bikes (Blur)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/bikes/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/bikes/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/bikes/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/bikes/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/bikes/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/bikes/2_2ORB_2ORB_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/bikes/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/bikes/2_1AKAZE_0SIFT_l2_bf.html) |
| AKAZE-AKAZE-HAM-BF | [JPG](/draws/bikes/2_1AKAZE_1AKAZE_ham_bf_.jpg) | [HTML](/draws/bikes/2_1AKAZE_1AKAZE_ham_bf.html) |

#### Boat (Zoom + Rotation)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/boat/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/boat/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/boat/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/boat/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/boat/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/boat/2_2ORB_2ORB_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/boat/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/boat/2_1AKAZE_0SIFT_l2_bf.html) |
| AGAST-BEBLID-HAM-BF | [JPG](/draws/boat/2_7AgastFeatureDetector_11BEBLID_ham_bf_.jpg) | [HTML](/draws/boat/2_7AgastFeatureDetector_11BEBLID_ham_bf.html) |

#### Graf (Viewpoint Change)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/graf/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/graf/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/graf/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/graf/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/graf/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/graf/2_2ORB_2ORB_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/graf/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/graf/2_1AKAZE_0SIFT_l2_bf.html) |
| AGAST-BEBLID-HAM-BF | [JPG](/draws/graf/2_7AgastFeatureDetector_11BEBLID_ham_bf_.jpg) | [HTML](/draws/graf/2_7AgastFeatureDetector_11BEBLID_ham_bf.html) |

#### Leuven (Illumination)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/leuven/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/leuven/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/leuven/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/leuven/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/leuven/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/leuven/2_2ORB_2ORB_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/leuven/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/leuven/2_1AKAZE_0SIFT_l2_bf.html) |
| AGAST-BEBLID-HAM-BF | [JPG](/draws/leuven/2_7AgastFeatureDetector_11BEBLID_ham_bf_.jpg) | [HTML](/draws/leuven/2_7AgastFeatureDetector_11BEBLID_ham_bf.html) |

#### Trees (Blur)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/trees/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/trees/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/trees/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/trees/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/trees/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/trees/2_2ORB_2ORB_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/trees/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/trees/2_1AKAZE_0SIFT_l2_bf.html) |
| AGAST-BEBLID-HAM-BF | [JPG](/draws/trees/2_7AgastFeatureDetector_11BEBLID_ham_bf_.jpg) | [HTML](/draws/trees/2_7AgastFeatureDetector_11BEBLID_ham_bf.html) |

#### UBC (JPEG Compression)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/ubc/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/ubc/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/ubc/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/ubc/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/ubc/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/ubc/2_2ORB_2ORB_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/ubc/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/ubc/2_1AKAZE_0SIFT_l2_bf.html) |
| AGAST-BEBLID-HAM-BF | [JPG](/draws/ubc/2_7AgastFeatureDetector_11BEBLID_ham_bf_.jpg) | [HTML](/draws/ubc/2_7AgastFeatureDetector_11BEBLID_ham_bf.html) |

#### Wall (Viewpoint Change)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/wall/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/wall/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/wall/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/wall/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/wall/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/wall/2_2ORB_2ORB_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/wall/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/wall/2_1AKAZE_0SIFT_l2_bf.html) |
| AGAST-BEBLID-HAM-BF | [JPG](/draws/wall/2_7AgastFeatureDetector_11BEBLID_ham_bf_.jpg) | [HTML](/draws/wall/2_7AgastFeatureDetector_11BEBLID_ham_bf.html) |

### Cross-Dataset Top Performers

| Algorithm Combination | Drone | UAV | AirSim | Oxford | Synthetic | Average |
|-----------------------|-------|-----|--------|--------|-----------|---------|
| ORB-BEBLID-HAM-BF | 0.801 | **0.725** | **0.806** | **0.626** | 0.800 | **0.752** |
| ORB-TEBLID-HAM-BF | 0.779 | 0.712 | 0.797 | 0.620 | 0.819 | 0.745 |
| ORB-ORB-HAM-BF | **0.803** | 0.673 | 0.637 | 0.604 | **0.854** | 0.714 |
| ORB-BEBLID-HAM-FLANN | 0.751 | 0.670 | 0.746 | 0.587 | 0.776 | 0.706 |
| AGAST-BEBLID-HAM-BF | 0.713 | 0.721 | 0.708 | 0.576 | 0.719 | 0.687 |
| MSD-BEBLID-HAM-BF | 0.660 | 0.691 | 0.755 | 0.571 | 0.742 | 0.684 |

### Unified Cross-Dataset Algorithm Ranking (Top 15)

| Rank | Algorithm | Mean | StdDev | Min | Max |
|------|-----------|------|--------|-----|-----|
| 1 | ORB-BEBLID-HAM-BF | **0.7517** | 0.0695 | 0.6264 | 0.8064 |
| 2 | ORB-TEBLID-HAM-BF | 0.7453 | 0.0720 | 0.6202 | 0.8188 |
| 3 | ORB-ORB-HAM-BF | 0.7141 | 0.0971 | 0.6038 | **0.8538** |
| 4 | ORB-BEBLID-HAM-FLANN | 0.7059 | 0.0692 | 0.5868 | 0.7756 |
| 5 | ORB-TEBLID-HAM-FLANN | 0.6990 | 0.0626 | 0.5902 | 0.7529 |
| 6 | AGAST-BEBLID-HAM-BF | 0.6874 | 0.0557 | 0.5763 | 0.7212 |
| 7 | MSD-BEBLID-HAM-BF | 0.6837 | 0.0660 | 0.5711 | 0.7547 |
| 8 | AGAST-TEBLID-HAM-BF | 0.6801 | 0.0557 | 0.5697 | 0.7179 |
| 9 | MSD-TEBLID-HAM-BF | 0.6777 | 0.0658 | 0.5649 | 0.7451 |
| 10 | ORB-ORB-HAM-FLANN | 0.6768 | 0.1026 | 0.5702 | 0.8335 |
| 11 | AKAZE-BEBLID-HAM-BF | 0.6694 | 0.0593 | 0.5734 | 0.7603 |
| 12 | ORB-BEBLID-L2-BF | 0.6658 | 0.0790 | 0.5581 | 0.7895 |
| 13 | AKAZE-TEBLID-HAM-BF | 0.6642 | 0.0603 | 0.5694 | 0.7599 |
| 14 | ORB-BOOST-HAM-BF | 0.6637 | 0.0998 | 0.5288 | 0.8157 |
| 15 | AKAZE-SIFT-L2-BF | 0.6633 | 0.0531 | 0.5792 | 0.7457 |

### Feature Detector Performance Rankings

| Rank | Detector | Mean CUES | Max CUES | Std | Evaluations |
|------|----------|-----------|----------|-----|-------------|
| 1 | AKAZE | **0.5455** | 0.7621 | **0.1520** | 175 |
| 2 | ORB | 0.5405 | **0.8538** | 0.1867 | 155 |
| 3 | STAR | 0.5304 | 0.8096 | 0.1541 | 153 |
| 4 | AGAST | 0.4974 | 0.7222 | 0.1572 | 153 |
| 5 | BRISK | 0.4796 | 0.7344 | 0.1656 | 153 |
| 6 | KAZE | 0.4722 | 0.7528 | 0.1646 | 176 |
| 7 | FAST | 0.4631 | 0.7199 | 0.1625 | 152 |
| 8 | SIFT | 0.4614 | 0.8229 | 0.1616 | 138 |
| 9 | MSD | 0.4449 | 0.7547 | 0.1833 | 141 |
| 10 | GFTT | 0.4318 | 0.7473 | 0.1884 | 151 |

### Feature Descriptor Performance Rankings

| Rank | Descriptor | Mean CUES | Max CUES | Std | Evaluations |
|------|------------|-----------|----------|-----|-------------|
| 1 | SIFT | **0.6147** | 0.7937 | **0.0786** | 126 |
| 2 | DAISY | 0.5972 | 0.7600 | 0.0943 | 137 |
| 3 | VGG | 0.5951 | 0.7915 | 0.1042 | 136 |
| 4 | BEBLID | 0.5881 | **0.8229** | 0.1076 | 204 |
| 5 | AKAZE | 0.5767 | 0.7568 | 0.0854 | 30 |
| 6 | TEBLID | 0.5658 | 0.8188 | 0.1266 | 203 |
| 7 | BOOST | 0.5464 | 0.8190 | 0.1263 | 204 |
| 8 | KAZE | 0.5190 | 0.6762 | 0.1744 | 13 |
| 9 | BRISK | 0.4009 | 0.8096 | 0.1675 | 186 |
| 10 | ORB | 0.3670 | 0.8538 | 0.1480 | 171 |

### Optimal Detector-Descriptor Combinations (Top 10)

| Rank | Combination | Mean CUES | Max CUES |
|------|-------------|-----------|----------|
| 1 | ORB-BEBLID | **0.7078** | **0.8064** |
| 2 | AKAZE-SIFT | 0.6625 | 0.7560 |
| 3 | STAR-SIFT | 0.6513 | 0.7348 |
| 4 | AKAZE-VGG | 0.6511 | 0.7575 |
| 5 | AGAST-SIFT | 0.6510 | 0.6984 |
| 6 | AGAST-VGG | 0.6457 | 0.7222 |
| 7 | AKAZE-AKAZE | 0.6401 | 0.7568 |
| 8 | AKAZE-DAISY | 0.6396 | 0.7059 |
| 9 | STAR-VGG | 0.6390 | 0.7414 |
| 10 | ORB-DAISY | 0.6343 | 0.7600 |

## Sensitivity Analysis

The CUES parameter choices are validated through systematic sensitivity analysis across all 5 datasets:

**Normalization Parameter $\alpha$ (Eq. 1-2):**
- Default $\alpha = 0.5$ (square root transformation)
- Stable across adjacent values: avg $\rho = 0.9845$
- Lowest correlation: synthetic $\rho = 0.9518$ ($\alpha=0.25$ vs $0.5$)
- Highest correlation: airsim $\rho = 0.9972$ ($\alpha=0.25$ vs $0.5$)

**Weight Aggregation Method (Eq. 11):**
- Default: arithmetic mean
- Highly stable across arithmetic, geometric, harmonic, and trimmed mean: avg $\rho = 0.9993$
- All weighting methods (Entropy, PCA, CRITIC, Variance) produce consistent rankings

**Most Consistent High Performers (Lowest Coefficient of Variation):**

| Rank | Algorithm | CoV | Mean | StdDev |
|------|-----------|-----|------|--------|
| 1 | AKAZE-SIFT-L2-BF | 0.0801 | 0.6633 | 0.0531 |
| 2 | AGAST-SIFT-L2-BF | 0.0802 | 0.6579 | 0.0528 |
| 3 | AGAST-BEBLID-HAM-BF | 0.0811 | 0.6874 | 0.0557 |
| 4 | BRISK-TEBLID-HAM-BF | 0.0815 | 0.6470 | 0.0527 |
| 5 | AGAST-TEBLID-HAM-BF | 0.0819 | 0.6801 | 0.0557 |
