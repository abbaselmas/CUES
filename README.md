# Towards Efficient 3D Reconstruction from UAV Imagery: Evaluation of OpenCV Feature Detection, Description and Matching Combinations

Author: Abbas Elmas  
PhD Thesis - Computer Vision and Photogrammetry  
Supported by: TÜBİTAK BİDEB 2211-A National PhD Scholarship Program

This repository contains experimental framework, datasets, evaluation outputs, and interactive visualizations for comprehensive evaluation of OpenCV feature detection, description, and matching algorithm combinations for UAV-based 3D reconstruction.

## Research Summary

- 784 algorithm combinations evaluated across 5 diverse datasets with 89 top performers visualized
- Composite Unsupervised Efficiency Score (CUES) - Entropy + CRITIC + PCA + Variance
- 6-Phase comprehensive analysis: Dataset-specific, Algorithm-specific, Component-based, Cross-dataset, Unified, Mobile-optimized
- Cross-dataset stability: 0.865 average correlation
- Cross-platform consistency: >0.994 correlation (desktop vs mobile vs mobile2)
- Best overall performer: ORB-ORB-HAM-BF (0.8821 synthetic)
- Best unified performer: ORB-BEBLID-HAM-BF (cross-dataset champion)
- Best UAV: GFTT-DAISY-L2-BF (0.7299)

## Interactive Dashboards

Access comprehensive analysis dashboards:

| Dataset | Main | Efficiency | Timing | Correlation | Heatmap | Violin |
|---------|------|------------|--------|-------------|---------|--------|
| Synthetic | [Analysis](/html/synthetic/synthetic.html) | [Efficiency](/html/synthetic/synthetic_Efficiency.html)    | [Timing](/html/synthetic/syntheticTiming.html) | [Correlation](/html/synthetic/synthetic_Correlation.html)  | [Heatmap](/html/synthetic/synthetic_Heatmap.html)  | [Violin](/html/synthetic/synthetic_Violin.html)    |
| Oxford    | [Analysis](/html/oxford/oxford.html)       | [Efficiency](/html/oxford/oxford_Efficiency.html)          | [Timing](/html/oxford/oxfordTiming.html)       | [Correlation](/html/oxford/oxford_Correlation.html)        | [Heatmap](/html/oxford/oxford_Heatmap.html)        | [Violin](/html/oxford/oxford_Violin.html)          |
| AirSim    | [Analysis](/html/airsim/airsim.html)       | [Efficiency](/html/airsim/airsim_Efficiency.html)          | [Timing](/html/airsim/airsimTiming.html)       | [Correlation](/html/airsim/airsim_Correlation.html)        | [Heatmap](/html/airsim/airsim_Heatmap.html)        | [Violin](/html/airsim/airsim_Violin.html)          |
| UAV       | [Analysis](/html/uav/uav.html)             | [Efficiency](/html/uav/uav_Efficiency.html)                | [Timing](/html/uav/uavTiming.html)             | [Correlation](/html/uav/uav_Correlation.html)              | [Heatmap](/html/uav/uav_Heatmap.html)              | [Violin](/html/uav/uav_Violin.html)                |
| Drone     | [Analysis](/html/drone/drone.html)         | [Efficiency](/html/drone/drone_Efficiency.html)            | [Timing](/html/drone/droneTiming.html)         | [Correlation](/html/drone/drone_Correlation.html)          | [Heatmap](/html/drone/drone_Heatmap.html)          | [Violin](/html/drone/drone_Violin.html)            |

### Detailed dashboards with variants and mobile analyses

| Dataset    | Main Page | Efficiency | Variants | Timing | Correlation | Heatmap | Violin |
|------------|-----------|------------|----------|--------|-------------|---------|--------|
| Synthetic | [synthetic](/html/synthetic/synthetic.html)                                   | [Efficiency](/html/synthetic/synthetic_Efficiency.html)               | [4](/html/synthetic/synthetic4.html), [All4](/html/synthetic/syntheticAll4.html)                                                              | [Timing](/html/synthetic/syntheticTiming.html)            | [Correlation](/html/synthetic/synthetic_Correlation.html)             | [Heatmap](/html/synthetic/synthetic_Heatmap.html)             | [Violin](/html/synthetic/synthetic_Violin.html)               |
| Synthetic | Mobile 1                                                                      | [Efficiency m1](/html/synthetic/synthetic_Efficiency_mobile.html)     | [4 m1](/html/synthetic/synthetic4_mobile.html), [All4 m1](/html/synthetic/syntheticAll4_mobile.html)                                          | [Timing m1](/html/synthetic/syntheticTiming_mobile.html)  | [Correlation m1](/html/synthetic/synthetic_Correlation_mobile.html)   | [Heatmap m1](/html/synthetic/synthetic_Heatmap_mobile.html)   | [Violin m1](/html/synthetic/synthetic_Violin_mobile.html)     |
| Synthetic | Mobile 2                                                                      | [Efficiency m2](/html/synthetic/synthetic_Efficiency_mobile2.html)    | [4 m2](/html/synthetic/synthetic4_mobile2.html), [All4 m2](/html/synthetic/syntheticAll4_mobile2.html)                                        | [Timing m2](/html/synthetic/syntheticTiming_mobile2.html) | [Correlation m2](/html/synthetic/synthetic_Correlation_mobile2.html)  | [Heatmap m2](/html/synthetic/synthetic_Heatmap_mobile2.html)  | [Violin m2](/html/synthetic/synthetic_Violin_mobile2.html)    |
| Oxford    | [oxford](/html/oxford/oxford.html)                                            | [Efficiency](/html/oxford/oxford_Efficiency.html)                     | [9](/html/oxford/oxford9.html), [All9](/html/oxford/oxfordAll9.html), [All](/html/oxford/oxfordAll.html)                                      | [Timing](/html/oxford/oxfordTiming.html)                  | [Correlation](/html/oxford/oxford_Correlation.html)                   | [Heatmap](/html/oxford/oxford_Heatmap.html)                   | [Violin](/html/oxford/oxford_Violin.html)                     |
| Oxford    | Mobile 1                                                                      | [Efficiency m1](/html/oxford/oxford_Efficiency_mobile.html)           | [9 m1](/html/oxford/oxford9_mobile.html),<br>[All9 m1](/html/oxford/oxfordAll9_mobile.html), [All m1](/html/oxford/oxfordAll_mobile.html)     | [Timing m1](/html/oxford/oxfordTiming_mobile.html)        | [Correlation m1](/html/oxford/oxford_Correlation_mobile.html)         | [Heatmap m1](/html/oxford/oxford_Heatmap_mobile.html)         | [Violin m1](/html/oxford/oxford_Violin_mobile.html)           |
| Oxford    | Mobile 2                                                                      | [Efficiency m2](/html/oxford/oxford_Efficiency_mobile2.html)          | [9 m2](/html/oxford/oxford9_mobile2.html),<br>[All9 m2](/html/oxford/oxfordAll9_mobile2.html), [All m2](/html/oxford/oxfordAll_mobile2.html)  | [Timing m2](/html/oxford/oxfordTiming_mobile2.html)       | [Correlation m2](/html/oxford/oxford_Correlation_mobile2.html)        | [Heatmap m2](/html/oxford/oxford_Heatmap_mobile2.html)        | [Violin m2](/html/oxford/oxford_Violin_mobile2.html)          |
| Drone     | [drone](/html/drone/drone.html)                                               | [Efficiency](/html/drone/drone_Efficiency.html)                       | [All](/html/drone/droneAll.html),         [AllXY](/html/drone/droneAllXY.html)                                                                | [Timing](/html/drone/droneTiming.html)                    | [Correlation](/html/drone/drone_Correlation.html)                     | [Heatmap](/html/drone/drone_Heatmap.html)                     | [Violin](/html/drone/drone_Violin.html)                       |
| UAV       | [uav](/html/uav/uav.html)                                                     | [Efficiency](/html/uav/uav_Efficiency.html)                           | [All](/html/uav/uavAll.html)                                                                                                                  | [Timing](/html/uav/uavTiming.html)                        | [Correlation](/html/uav/uav_Correlation.html)                         | [Heatmap](/html/uav/uav_Heatmap.html)                         | [Violin](/html/uav/uav_Violin.html)                           |
| AirSim    | [airsim](/html/airsim/airsim.html)                                            | [Efficiency](/html/airsim/airsim_Efficiency.html)                     | [All](/html/airsim/airsimAll.html)                                                                                                            | [Timing](/html/airsim/airsimTiming.html)                  | [Correlation](/html/airsim/airsim_Correlation.html)                   | [Heatmap](/html/airsim/airsim_Heatmap.html)                   | [Violin](/html/airsim/airsim_Violin.html)                     |

## Feature Matching Visualizations

Interactive JPG and HTML visualizations for 135+ top-performing algorithm combinations across 784 evaluated configurations. Each visualization includes match quality metrics, timing statistics, and toggleable information overlays.

### Top 5 Algorithm Combinations per Dataset

| Dataset | Rank | Algorithm Combination | CUES | Static | Interactive |
|---------|------|-----------------------|------|--------|-------------|
| **Synthetic** | 1 | ORB-ORB-HAM-BF | 0.8821 | [JPG](/draws/rot/woman_4_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| | 2 | ORB-ORB-HAM-FLANN | 0.8789 | [JPG](/draws/rot/woman_4_2ORB_2ORB_ham_flann_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_flann.html) |
| | 3 | ORB-TEBLID-HAM-BF | 0.8445 | [JPG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html) |
| | 4 | ORB-BOOST-HAM-BF | 0.8412 | [JPG](/draws/rot/woman_4_2ORB_13BOOST_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.html) |
| | 5 | STAR-BRISK-HAM-BF | 0.8383 | [JPG](/draws/rot/woman_4_10STAR_3BRISK_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.html) |
| **Oxford** | 1 | ORB-BEBLID-HAM-BF | 0.6219 | [JPG](/draws/bark/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_11BEBLID_ham_bf.html) |
| | 2 | ORB-TEBLID-HAM-BF | 0.6152 | [JPG](/draws/bark/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_12TEBLID_ham_bf.html) |
| | 3 | AKAZE-SIFT-L2-BF | 0.6078 | [JPG](/draws/bark/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/bark/2_1AKAZE_0SIFT_l2_bf.html) |
| | 4 | ORB-TEBLID-HAM-FLANN | 0.6058 | [JPG](/draws/bark/2_2ORB_12TEBLID_ham_flann_.jpg) | [HTML](/draws/bark/2_2ORB_12TEBLID_ham_flann.html) |
| | 5 | ORB-BEBLID-HAM-FLANN | 0.6027 | [JPG](/draws/bark/2_2ORB_11BEBLID_ham_flann_.jpg) | [HTML](/draws/bark/2_2ORB_11BEBLID_ham_flann.html) |
| **AirSim** | 1 | ORB-BEBLID-HAM-BF | 0.7891 | [JPG](/draws/airsim/2_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_bf.html) |
| | 2 | ORB-TEBLID-HAM-BF | 0.7782 | [JPG](/draws/airsim/2_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_bf.html) |
| | 3 | ORB-BEBLID-HAM-FLANN | 0.7650 | [JPG](/draws/airsim/2_2ORB_11BEBLID_ham_flann.jpg) | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_flann.html) |
| | 4 | ORB-TEBLID-HAM-FLANN | 0.7635 | [JPG](/draws/airsim/2_2ORB_12TEBLID_ham_flann.jpg) | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_flann.html) |
| | 5 | KAZE-SIFT-L2-BF | 0.7614 | [JPG](/draws/airsim/2_4KAZE_0SIFT_l2_bf.jpg) | [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_bf.html) |
| **UAV** | 1 | GFTT-DAISY-L2-BF | 0.7299 | [JPG](/draws/uav/8_8GFTTDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_8GFTTDetector_5DAISY_l2_bf.html) |
| | 2 | AGAST-SIFT-L2-BF | 0.7255 | [JPG](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.html) |
| | 3 | AKAZE-DAISY-L2-BF | 0.7189 | [JPG](/draws/uav/8_1AKAZE_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_1AKAZE_5DAISY_l2_bf.html) |
| | 4 | FAST-SIFT-L2-BF | 0.7161 | [JPG](/draws/uav/8_5FastFeatureDetector_0SIFT_l2_bf.jpg) | [HTML](/draws/uav/8_5FastFeatureDetector_0SIFT_l2_bf.html) |
| | 5 | AGAST-DAISY-L2-BF | 0.7124 | [JPG](/draws/uav/8_7AgastFeatureDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_5DAISY_l2_bf.html) |
| **Drone** | 1 | ORB-BEBLID-HAM-BF | 0.8489 | [JPG](/draws/drone/17_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_bf.html) |
| | 2 | ORB-DAISY-L2-BF | 0.8286 | [JPG](/draws/drone/17_2ORB_5DAISY_l2_bf.jpg) | [HTML](/draws/drone/17_2ORB_5DAISY_l2_bf.html) |
| | 3 | ORB-TEBLID-HAM-BF | 0.8247 | [JPG](/draws/drone/17_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_12TEBLID_ham_bf.html) |
| | 4 | ORB-BEBLID-HAM-FLANN | 0.8209 | [JPG](/draws/drone/17_2ORB_11BEBLID_ham_flann.jpg) | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_flann.html) |
| | 5 | GFTT-DAISY-L2-BF | 0.8155 | [JPG](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.html) |

### Drone Dataset Visualizations

| Algorithm Combination | CUES | Static | Interactive |
|-----------------------|------|--------|-------------|
| ORB-BEBLID-HAM-BF | 0.8489 | [JPG](/draws/drone/17_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_bf.html) |
| ORB-DAISY-L2-BF | 0.8286 | [JPG](/draws/drone/17_2ORB_5DAISY_l2_bf.jpg) | [HTML](/draws/drone/17_2ORB_5DAISY_l2_bf.html) |
| ORB-TEBLID-HAM-BF | 0.8247 | [JPG](/draws/drone/17_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_12TEBLID_ham_bf.html) |
| ORB-BEBLID-HAM-FLANN | 0.8209 | [JPG](/draws/drone/17_2ORB_11BEBLID_ham_flann.jpg) | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_flann.html) |
| GFTT-DAISY-L2-BF | 0.8155 | [JPG](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.html) |
| ORB-TEBLID-HAM-FLANN | 0.8100 | [JPG](/draws/drone/17_2ORB_12TEBLID_ham_flann.jpg) | [HTML](/draws/drone/17_2ORB_12TEBLID_ham_flann.html) |
| ORB-DAISY-L2-FLANN | 0.8053 | [JPG](/draws/drone/17_2ORB_5DAISY_l2_flann.jpg) | [HTML](/draws/drone/17_2ORB_5DAISY_l2_flann.html) |
| ORB-ORB-HAM-BF | 0.7979 | [JPG](/draws/drone/17_2ORB_2ORB_ham_bf.jpg) | [HTML](/draws/drone/17_2ORB_2ORB_ham_bf.html) |
| GFTT-DAISY-L2-FLANN | 0.7952 | [JPG](/draws/drone/17_8GFTTDetector_5DAISY_l2_flann.jpg) | [HTML](/draws/drone/17_8GFTTDetector_5DAISY_l2_flann.html) |
| ORB-ORB-HAM-FLANN | 0.7788 | [JPG](/draws/drone/17_2ORB_2ORB_ham_flann.jpg) | [HTML](/draws/drone/17_2ORB_2ORB_ham_flann.html) |

### UAV Dataset Visualizations

| Algorithm Combination | CUES | Static | Interactive |
|-----------------------|------|--------|-------------|
| GFTT-DAISY-L2-BF | 0.7299 | [JPG](/draws/uav/8_8GFTTDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_8GFTTDetector_5DAISY_l2_bf.html) |
| AGAST-SIFT-L2-BF | 0.7255 | [JPG](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.html) |
| AKAZE-DAISY-L2-BF | 0.7189 | [JPG](/draws/uav/8_1AKAZE_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_1AKAZE_5DAISY_l2_bf.html) |
| FAST-SIFT-L2-BF | 0.7161 | [JPG](/draws/uav/8_5FastFeatureDetector_0SIFT_l2_bf.jpg) | [HTML](/draws/uav/8_5FastFeatureDetector_0SIFT_l2_bf.html) |
| AGAST-DAISY-L2-BF | 0.7124 | [JPG](/draws/uav/8_7AgastFeatureDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_5DAISY_l2_bf.html) |
| BRISK-DAISY-L2-BF | 0.7122 | [JPG](/draws/uav/8_3BRISK_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_3BRISK_5DAISY_l2_bf.html) |
| AGAST-VGG-L2-BF | 0.7079 | [JPG](/draws/uav/8_7AgastFeatureDetector_10VGG_l2_bf.jpg) | [HTML](/draws/uav/8_7AgastFeatureDetector_10VGG_l2_bf.html) |
| KAZE-SIFT-L2-BF | 0.7064 | [JPG](/draws/uav/8_4KAZE_0SIFT_l2_bf.jpg) | [HTML](/draws/uav/8_4KAZE_0SIFT_l2_bf.html) |
| AKAZE-DAISY-L2-FLANN | 0.7062 | [JPG](/draws/uav/8_1AKAZE_5DAISY_l2_flann.jpg) | [HTML](/draws/uav/8_1AKAZE_5DAISY_l2_flann.html) |
| GFTT_H-DAISY-L2-BF | 0.7041 | [JPG](/draws/uav/8_9GFTTDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/uav/8_9GFTTDetector_5DAISY_l2_bf.html) |

### AirSim Dataset Visualizations

| Algorithm Combination | CUES | Static | Interactive |
|-----------------------|------|--------|-------------|
| ORB-BEBLID-HAM-BF | 0.7891 | [JPG](/draws/airsim/2_2ORB_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | 0.7782 | [JPG](/draws/airsim/2_2ORB_12TEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_bf.html) |
| ORB-BEBLID-HAM-FLANN | 0.7650 | [JPG](/draws/airsim/2_2ORB_11BEBLID_ham_flann.jpg) | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_flann.html) |
| ORB-TEBLID-HAM-FLANN | 0.7635 | [JPG](/draws/airsim/2_2ORB_12TEBLID_ham_flann.jpg) | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_flann.html) |
| KAZE-SIFT-L2-BF | 0.7614 | [JPG](/draws/airsim/2_4KAZE_0SIFT_l2_bf.jpg) | [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-DAISY-L2-BF | 0.7436 | [JPG](/draws/airsim/2_8GFTTDetector_5DAISY_l2_bf.jpg) | [HTML](/draws/airsim/2_8GFTTDetector_5DAISY_l2_bf.html) |
| KAZE-SIFT-L2-FLANN | 0.7412 | [JPG](/draws/airsim/2_4KAZE_0SIFT_l2_flann.jpg) | [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_flann.html) |
| KAZE-BEBLID-HAM-BF | 0.7386 | [JPG](/draws/airsim/2_4KAZE_11BEBLID_ham_bf.jpg) | [HTML](/draws/airsim/2_4KAZE_11BEBLID_ham_bf.html) |
| AGAST-SIFT-L2-BF | 0.7359 | [JPG](/draws/airsim/2_7AgastFeatureDetector_0SIFT_l2_bf.jpg) | [HTML](/draws/airsim/2_7AgastFeatureDetector_0SIFT_l2_bf.html) |
| AKAZE-DAISY-L2-BF | 0.7299 | [JPG](/draws/airsim/2_1AKAZE_5DAISY_l2_bf.jpg) | [HTML](/draws/airsim/2_1AKAZE_5DAISY_l2_bf.html) |

### Synthetic Dataset Visualizations (Rotation)

| Algorithm Combination | CUES | Static | Interactive |
|-----------------------|------|--------|-------------|
| ORB-ORB-HAM-BF | 0.8821 | [JPG](/draws/rot/woman_4_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| ORB-ORB-HAM-FLANN | 0.8789 | [JPG](/draws/rot/woman_4_2ORB_2ORB_ham_flann_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_flann.html) |
| ORB-TEBLID-HAM-BF | 0.8445 | [JPG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html) |
| ORB-BOOST-HAM-BF | 0.8412 | [JPG](/draws/rot/woman_4_2ORB_13BOOST_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.html) |
| STAR-BRISK-HAM-BF | 0.8383 | [JPG](/draws/rot/woman_4_10STAR_3BRISK_ham_bf_.jpg) | [HTML](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.html) |
| ORB-VGG-L2-BF | 0.8367 | [JPG](/draws/rot/woman_4_2ORB_10VGG_l2_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_10VGG_l2_bf.html) |
| ORB-VGG-L2-FLANN | 0.8362 | [JPG](/draws/rot/woman_4_2ORB_10VGG_l2_flann_.jpg) | [HTML](/draws/rot/woman_4_2ORB_10VGG_l2_flann.html) |
| STAR-BRISK-HAM-FLANN | 0.8359 | [JPG](/draws/rot/woman_4_10STAR_3BRISK_ham_flann_.jpg) | [HTML](/draws/rot/woman_4_10STAR_3BRISK_ham_flann.html) |
| ORB-ORB-L2-BF | 0.8343 | [JPG](/draws/rot/woman_4_2ORB_2ORB_l2_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_2ORB_l2_bf.html) |
| ORB-BEBLID-L2-BF | 0.8304 | [JPG](/draws/rot/woman_4_2ORB_11BEBLID_l2_bf_.jpg) | [HTML](/draws/rot/woman_4_2ORB_11BEBLID_l2_bf.html) |

### Synthetic Dataset Visualizations (Scale)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-ORB-HAM-BF | [JPG](/draws/scale/woman_4_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/scale/woman_4_2ORB_2ORB_ham_bf.html) |
| ORB-ORB-HAM-FLANN | [JPG](/draws/scale/woman_4_2ORB_2ORB_ham_flann_.jpg) | [HTML](/draws/scale/woman_4_2ORB_2ORB_ham_flann.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/scale/woman_4_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/scale/woman_4_2ORB_12TEBLID_ham_bf.html) |
| ORB-BOOST-HAM-BF | [JPG](/draws/scale/woman_4_2ORB_13BOOST_ham_bf_.jpg) | [HTML](/draws/scale/woman_4_2ORB_13BOOST_ham_bf.html) |
| STAR-BRISK-HAM-BF | [JPG](/draws/scale/woman_4_10STAR_3BRISK_ham_bf_.jpg) | [HTML](/draws/scale/woman_4_10STAR_3BRISK_ham_bf.html) |
| ORB-VGG-L2-BF | [JPG](/draws/scale/woman_4_2ORB_10VGG_l2_bf_.jpg) | [HTML](/draws/scale/woman_4_2ORB_10VGG_l2_bf.html) |
| ORB-VGG-L2-FLANN | [JPG](/draws/scale/woman_4_2ORB_10VGG_l2_flann_.jpg) | [HTML](/draws/scale/woman_4_2ORB_10VGG_l2_flann.html) |
| STAR-BRISK-HAM-FLANN | [JPG](/draws/scale/woman_4_10STAR_3BRISK_ham_flann_.jpg) | [HTML](/draws/scale/woman_4_10STAR_3BRISK_ham_flann.html) |
| ORB-ORB-L2-BF | [JPG](/draws/scale/woman_4_2ORB_2ORB_l2_bf_.jpg) | [HTML](/draws/scale/woman_4_2ORB_2ORB_l2_bf.html) |
| ORB-BEBLID-L2-BF | [JPG](/draws/scale/woman_4_2ORB_11BEBLID_l2_bf_.jpg) | [HTML](/draws/scale/woman_4_2ORB_11BEBLID_l2_bf.html) |

### Synthetic Dataset Visualizations (Intensity)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-ORB-HAM-BF | [JPG](/draws/intensity/woman_7_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/intensity/woman_7_2ORB_2ORB_ham_bf.html) |
| ORB-ORB-HAM-FLANN | [JPG](/draws/intensity/woman_7_2ORB_2ORB_ham_flann_.jpg) | [HTML](/draws/intensity/woman_7_2ORB_2ORB_ham_flann.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/intensity/woman_7_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/intensity/woman_7_2ORB_12TEBLID_ham_bf.html) |
| ORB-BOOST-HAM-BF | [JPG](/draws/intensity/woman_7_2ORB_13BOOST_ham_bf_.jpg) | [HTML](/draws/intensity/woman_7_2ORB_13BOOST_ham_bf.html) |
| STAR-BRISK-HAM-BF | [JPG](/draws/intensity/woman_7_10STAR_3BRISK_ham_bf_.jpg) | [HTML](/draws/intensity/woman_7_10STAR_3BRISK_ham_bf.html) |
| ORB-VGG-L2-BF | [JPG](/draws/intensity/woman_7_2ORB_10VGG_l2_bf_.jpg) | [HTML](/draws/intensity/woman_7_2ORB_10VGG_l2_bf.html) |
| ORB-VGG-L2-FLANN | [JPG](/draws/intensity/woman_7_2ORB_10VGG_l2_flann_.jpg) | [HTML](/draws/intensity/woman_7_2ORB_10VGG_l2_flann.html) |
| STAR-BRISK-HAM-FLANN | [JPG](/draws/intensity/woman_7_10STAR_3BRISK_ham_flann_.jpg) | [HTML](/draws/intensity/woman_7_10STAR_3BRISK_ham_flann.html) |
| ORB-ORB-L2-BF | [JPG](/draws/intensity/woman_7_2ORB_2ORB_l2_bf_.jpg) | [HTML](/draws/intensity/woman_7_2ORB_2ORB_l2_bf.html) |
| ORB-BEBLID-L2-BF | [JPG](/draws/intensity/woman_7_2ORB_11BEBLID_l2_bf_.jpg) | [HTML](/draws/intensity/woman_7_2ORB_11BEBLID_l2_bf.html) |

### Oxford Affine Dataset Visualizations

#### Bark (Viewpoint Change)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/bark/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/bark/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_12TEBLID_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/bark/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/bark/2_1AKAZE_0SIFT_l2_bf.html) |
| AKAZE-SIFT-L2-FLANN | [JPG](/draws/bark/2_1AKAZE_0SIFT_l2_flann_.jpg) | [HTML](/draws/bark/2_1AKAZE_0SIFT_l2_flann.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/bark/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/bark/2_2ORB_2ORB_ham_bf.html) |
| ORB-ORB-HAM-FLANN | [JPG](/draws/bark/2_2ORB_2ORB_ham_flann_.jpg) | [HTML](/draws/bark/2_2ORB_2ORB_ham_flann.html) |
| KAZE-SIFT-L2-BF | [JPG](/draws/bark/2_4KAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/bark/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-SIFT-L2-BF | [JPG](/draws/bark/2_8GFTTDetector_0SIFT_l2_bf_.jpg) | [HTML](/draws/bark/2_8GFTTDetector_0SIFT_l2_bf.html) |

#### Bikes (Blur)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/bikes/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/bikes/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/bikes/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/bikes/2_2ORB_12TEBLID_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/bikes/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/bikes/2_1AKAZE_0SIFT_l2_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/bikes/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/bikes/2_2ORB_2ORB_ham_bf.html) |
| KAZE-SIFT-L2-BF | [JPG](/draws/bikes/2_4KAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/bikes/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-SIFT-L2-BF | [JPG](/draws/bikes/2_8GFTTDetector_0SIFT_l2_bf_.jpg) | [HTML](/draws/bikes/2_8GFTTDetector_0SIFT_l2_bf.html) |

#### Boat (Zoom + Rotation)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/boat/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/boat/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/boat/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/boat/2_2ORB_12TEBLID_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/boat/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/boat/2_1AKAZE_0SIFT_l2_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/boat/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/boat/2_2ORB_2ORB_ham_bf.html) |
| KAZE-SIFT-L2-BF | [JPG](/draws/boat/2_4KAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/boat/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-SIFT-L2-BF | [JPG](/draws/boat/2_8GFTTDetector_0SIFT_l2_bf_.jpg) | [HTML](/draws/boat/2_8GFTTDetector_0SIFT_l2_bf.html) |

#### Graf (Viewpoint Change)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/graf/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/graf/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/graf/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/graf/2_2ORB_12TEBLID_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/graf/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/graf/2_1AKAZE_0SIFT_l2_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/graf/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/graf/2_2ORB_2ORB_ham_bf.html) |
| KAZE-SIFT-L2-BF | [JPG](/draws/graf/2_4KAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/graf/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-SIFT-L2-BF | [JPG](/draws/graf/2_8GFTTDetector_0SIFT_l2_bf_.jpg) | [HTML](/draws/graf/2_8GFTTDetector_0SIFT_l2_bf.html) |

#### Leuven (Illumination)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/leuven/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/leuven/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/leuven/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/leuven/2_2ORB_12TEBLID_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/leuven/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/leuven/2_1AKAZE_0SIFT_l2_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/leuven/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/leuven/2_2ORB_2ORB_ham_bf.html) |
| KAZE-SIFT-L2-BF | [JPG](/draws/leuven/2_4KAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/leuven/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-SIFT-L2-BF | [JPG](/draws/leuven/2_8GFTTDetector_0SIFT_l2_bf_.jpg) | [HTML](/draws/leuven/2_8GFTTDetector_0SIFT_l2_bf.html) |

#### Trees (Blur)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/trees/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/trees/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/trees/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/trees/2_2ORB_12TEBLID_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/trees/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/trees/2_1AKAZE_0SIFT_l2_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/trees/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/trees/2_2ORB_2ORB_ham_bf.html) |
| KAZE-SIFT-L2-BF | [JPG](/draws/trees/2_4KAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/trees/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-SIFT-L2-BF | [JPG](/draws/trees/2_8GFTTDetector_0SIFT_l2_bf_.jpg) | [HTML](/draws/trees/2_8GFTTDetector_0SIFT_l2_bf.html) |

#### UBC (JPEG Compression)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/ubc/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/ubc/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/ubc/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/ubc/2_2ORB_12TEBLID_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/ubc/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/ubc/2_1AKAZE_0SIFT_l2_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/ubc/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/ubc/2_2ORB_2ORB_ham_bf.html) |
| KAZE-SIFT-L2-BF | [JPG](/draws/ubc/2_4KAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/ubc/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-SIFT-L2-BF | [JPG](/draws/ubc/2_8GFTTDetector_0SIFT_l2_bf_.jpg) | [HTML](/draws/ubc/2_8GFTTDetector_0SIFT_l2_bf.html) |

#### Wall (Viewpoint Change)

| Algorithm Combination | Static | Interactive |
|-----------------------|--------|-------------|
| ORB-BEBLID-HAM-BF | [JPG](/draws/wall/2_2ORB_11BEBLID_ham_bf_.jpg) | [HTML](/draws/wall/2_2ORB_11BEBLID_ham_bf.html) |
| ORB-TEBLID-HAM-BF | [JPG](/draws/wall/2_2ORB_12TEBLID_ham_bf_.jpg) | [HTML](/draws/wall/2_2ORB_12TEBLID_ham_bf.html) |
| AKAZE-SIFT-L2-BF | [JPG](/draws/wall/2_1AKAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/wall/2_1AKAZE_0SIFT_l2_bf.html) |
| ORB-ORB-HAM-BF | [JPG](/draws/wall/2_2ORB_2ORB_ham_bf_.jpg) | [HTML](/draws/wall/2_2ORB_2ORB_ham_bf.html) |
| KAZE-SIFT-L2-BF | [JPG](/draws/wall/2_4KAZE_0SIFT_l2_bf_.jpg) | [HTML](/draws/wall/2_4KAZE_0SIFT_l2_bf.html) |
| GFTT-SIFT-L2-BF | [JPG](/draws/wall/2_8GFTTDetector_0SIFT_l2_bf_.jpg) | [HTML](/draws/wall/2_8GFTTDetector_0SIFT_l2_bf.html) |

### Cross-Dataset Top Performers

| Algorithm Combination | Drone | UAV | AirSim | Oxford | Synthetic | Average |
|-----------------------|-------|-----|--------|--------|-----------|---------|
| ORB-BEBLID-HAM-BF | **0.849** | 0.704 | **0.789** | **0.622** | 0.825 | 0.758 |
| ORB-TEBLID-HAM-BF | 0.825 | 0.691 | 0.778 | 0.615 | **0.844** | 0.751 |
| ORB-BEBLID-HAM-FLANN | 0.821 | 0.679 | 0.765 | 0.603 | 0.818 | 0.737 |
| ORB-TEBLID-HAM-FLANN | 0.810 | 0.677 | 0.764 | 0.606 | 0.793 | 0.730 |
| AKAZE-SIFT-L2-BF | 0.717 | 0.703 | 0.681 | 0.608 | 0.809 | 0.704 |
| GFTT-DAISY-L2-BF | 0.816 | **0.730** | 0.744 | 0.504 | 0.728 | 0.704 |

### Feature Detector Performance Rankings

| Rank | Detector | Mean CUES | Max CUES | Std | Evaluations |
|------|----------|-----------|----------|-----|-------------|
| 1 | AKAZE | 0.5472 | 0.8092 | **0.1771** | 179 |
| 2 | ORB | 0.5297 | **0.8821** | 0.2168 | 163 |
| 3 | STAR | 0.5070 | 0.8383 | 0.1840 | 165 |
| 4 | AGAST | 0.4696 | 0.7638 | 0.1791 | 165 |
| 5 | BRISK | 0.4640 | 0.7855 | 0.1961 | 164 |
| 6 | KAZE | 0.4614 | 0.7614 | 0.1910 | 186 |
| 7 | FAST | 0.4339 | 0.7773 | 0.1841 | 164 |
| 8 | SIFT | 0.4237 | 0.8001 | 0.1803 | 149 |
| 9 | MSD | 0.4044 | 0.7283 | 0.2015 | 155 |
| 10 | GFTT | 0.4017 | 0.8155 | 0.2126 | 162 |

### Feature Descriptor Performance Rankings

| Rank | Descriptor | Mean CUES | Max CUES | Std | Evaluations |
|------|------------|-----------|----------|-----|-------------|
| 1 | SIFT | 0.6354 | 0.8092 | 0.0966 | 129 |
| 2 | DAISY | 0.6213 | 0.8286 | 0.1089 | 140 |
| 3 | VGG | 0.6024 | 0.8367 | 0.1216 | 140 |
| 4 | KAZE | 0.6002 | 0.7259 | 0.1401 | 11 |
| 5 | AKAZE | 0.5894 | 0.8014 | **0.0944** | 30 |
| 6 | BEBLID | 0.5801 | **0.8489** | 0.1237 | 210 |
| 7 | TEBLID | 0.5535 | 0.8445 | 0.1446 | 210 |
| 8 | BOOST | 0.5337 | 0.8412 | 0.1434 | 210 |
| 9 | BRISK | 0.3677 | 0.8383 | 0.1855 | 206 |
| 10 | ORB | 0.3344 | 0.8821 | 0.1588 | 188 |

### Optimal Detector-Descriptor Combinations (Top 10)

| Rank | Combination | Mean CUES | Max CUES |
|------|-------------|-----------|----------|
| 1 | AKAZE-SIFT | 0.6947 | 0.8092 |
| 2 | AGAST-SIFT | 0.6801 | 0.7507 |
| 3 | STAR-SIFT | 0.6787 | 0.7719 |
| 4 | ORB-DAISY | 0.6785 | **0.8286** |
| 5 | AKAZE-VGG | 0.6765 | 0.8090 |
| 6 | ORB-SIFT | 0.6758 | 0.7670 |
| 7 | AKAZE-DAISY | 0.6730 | 0.7315 |
| 8 | STAR-DAISY | 0.6651 | 0.7383 |
| 9 | BRISK-SIFT | 0.6643 | 0.7733 |
| 10 | BRISK-DAISY | 0.6637 | 0.7624 |
