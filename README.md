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

*Comprehensive visualization coverage based on all 6 phases of framework analysis - 89 total algorithm combinations across 12 recommendation categories*

### Phase 1: Dataset-Specific Top Performers

#### Drone Dataset

| Rank | Algorithm | Efficiency | PNG | HTML |
|------|-----------|------------|-----|------|
| 1 | orb-beblid-ham-bf     | 0.8489 | [PNG](/draws/drone/17_2ORB_11BEBLID_ham_bf.png)          | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_bf.html)         |
| 2 | orb-daisy-l2-bf       | 0.8286 | [PNG](/draws/drone/17_2ORB_5DAISY_l2_bf.png)             | [HTML](/draws/drone/17_2ORB_5DAISY_l2_bf.html)            |
| 3 | orb-teblid-ham-bf     | 0.8247 | [PNG](/draws/drone/17_2ORB_12TEBLID_ham_bf.png)          | [HTML](/draws/drone/17_2ORB_12TEBLID_ham_bf.html)         |
| 4 | orb-beblid-ham-flann  | 0.8209 | [PNG](/draws/drone/17_2ORB_11BEBLID_ham_flann.png)       | [HTML](/draws/drone/17_2ORB_11BEBLID_ham_flann.html)      |
| 5 | gftt-daisy-l2-bf      | 0.8155 | [PNG](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.png)    | [HTML](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.html)   |

#### UAV Dataset

| Rank | Algorithm | Efficiency | PNG | HTML |
|------|-----------|------------|-----|------|
| 1 | gftt-daisy-l2-bf  | 0.7299 | [PNG](/draws/uav/8_8GFTTDetector_5DAISY_l2_bf.png)           | [HTML](/draws/uav/8_8GFTTDetector_5DAISY_l2_bf.html)          |
| 2 | agast-sift-l2-bf  | 0.7255 | [PNG](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.png)    | [HTML](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.html)   |
| 3 | akaze-daisy-l2-bf | 0.7189 | [PNG](/draws/uav/8_1AKAZE_5DAISY_l2_bf.png)                  | [HTML](/draws/uav/8_1AKAZE_5DAISY_l2_bf.html)                 |
| 4 | fast-sift-l2-bf   | 0.7161 | [PNG](/draws/uav/8_5FastFeatureDetector_0SIFT_l2_bf.png)     | [HTML](/draws/uav/8_5FastFeatureDetector_0SIFT_l2_bf.html)    |
| 5 | agast-daisy-l2-bf | 0.7124 | [PNG](/draws/uav/8_7AgastFeatureDetector_5DAISY_l2_bf.png)   | [HTML](/draws/uav/8_7AgastFeatureDetector_5DAISY_l2_bf.html)  |

#### AirSim Dataset

| Rank | Algorithm | Efficiency | PNG | HTML |
|------|-----------|------------|-----|------|
| 1 | orb-beblid-ham-bf     | 0.7891 | [PNG](/draws/airsim/2_2ORB_11BEBLID_ham_bf.png)          | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_bf.html)         |
| 2 | orb-teblid-ham-bf     | 0.7782 | [PNG](/draws/airsim/2_2ORB_12TEBLID_ham_bf.png)          | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_bf.html)         |
| 3 | orb-beblid-ham-flann  | 0.7650 | [PNG](/draws/airsim/2_2ORB_11BEBLID_ham_flann.png)       | [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_flann.html)      |
| 4 | orb-teblid-ham-flann  | 0.7635 | [PNG](/draws/airsim/2_2ORB_12TEBLID_ham_flann.png)       | [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_flann.html)      |
| 5 | kaze-sift-l2-bf       | 0.7614 | [PNG](/draws/airsim/2_4KAZE_0SIFT_l2_bf.png)             | [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_bf.html)            |
| 6 | gftt-daisy-l2-bf      | 0.7436 | [PNG](/draws/airsim/2_8GFTTDetector_5DAISY_l2_bf.png)    | [HTML](/draws/airsim/2_8GFTTDetector_5DAISY_l2_bf.html)   |

#### Oxford Dataset

| Rank | Algorithm | Efficiency | Boat Scenario | Wall Scenario |
|------|-----------|------------|---------------|---------------|
| 1 | orb-beblid-ham-bf     | 0.6219 | [PNG](/draws/boat/2_2ORB_11BEBLID_ham_bf.png)    / [HTML](/draws/boat/2_2ORB_11BEBLID_ham_bf.html)       | [PNG](/draws/wall/2_2ORB_11BEBLID_ham_bf.png)     / [HTML](/draws/wall/2_2ORB_11BEBLID_ham_bf.html)       |
| 2 | orb-teblid-ham-bf     | 0.6152 | [PNG](/draws/boat/2_2ORB_12TEBLID_ham_bf.png)    / [HTML](/draws/boat/2_2ORB_12TEBLID_ham_bf.html)       | [PNG](/draws/wall/2_2ORB_12TEBLID_ham_bf.png)     / [HTML](/draws/wall/2_2ORB_12TEBLID_ham_bf.html)       |
| 3 | akaze-sift-l2-bf      | 0.6078 | [PNG](/draws/boat/2_1AKAZE_0SIFT_l2_bf.png)      / [HTML](/draws/boat/2_1AKAZE_0SIFT_l2_bf.html)         | [PNG](/draws/wall/2_1AKAZE_0SIFT_l2_bf.png)       / [HTML](/draws/wall/2_1AKAZE_0SIFT_l2_bf.html)         |
| 4 | orb-teblid-ham-flann  | 0.6058 | [PNG](/draws/boat/2_2ORB_12TEBLID_ham_flann.png) / [HTML](/draws/boat/2_2ORB_12TEBLID_ham_flann.html)    | [PNG](/draws/wall/2_2ORB_12TEBLID_ham_flann.png)  / [HTML](/draws/wall/2_2ORB_12TEBLID_ham_flann.html)    |
| 5 | orb-beblid-ham-flann  | 0.6027 | [PNG](/draws/boat/2_2ORB_11BEBLID_ham_flann.png) / [HTML](/draws/boat/2_2ORB_11BEBLID_ham_flann.html)    | [PNG](/draws/wall/2_2ORB_11BEBLID_ham_flann.png)  / [HTML](/draws/wall/2_2ORB_11BEBLID_ham_flann.html)    |

#### Synthetic Dataset

| Rank | Algorithm | Efficiency | Rotation Scenario | Scale Scenario |
|------|-----------|------------|-------------------|----------------|
| 1 | orb-orb-ham-bf  | 0.8821 | [PNG](/draws/rot/woman_4_2ORB_2ORB_ham_bf.png)       / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html)      | [PNG](/draws/scale/woman_5_2ORB_2ORB_ham_bf.png)      / [HTML](/draws/scale/woman_5_2ORB_2ORB_ham_bf.html)        |
| 2 | orb-orb-ham-flann | 0.8789 | [PNG](/draws/rot/woman_4_2ORB_2ORB_ham_flann.png)    / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_flann.html)   | [PNG](/draws/scale/woman_5_2ORB_2ORB_ham_flann.png)   / [HTML](/draws/scale/woman_5_2ORB_2ORB_ham_flann.html)     |
| 3 | orb-teblid-ham-bf | 0.8445 | [PNG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.png)   / [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html)  | [PNG](/draws/scale/woman_5_2ORB_12TEBLID_ham_bf.png)  / [HTML](/draws/scale/woman_5_2ORB_12TEBLID_ham_bf.html)    |
| 4 | orb-boost-ham-bf  | 0.8412 | [PNG](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.png)    / [HTML](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.html)   | [PNG](/draws/scale/woman_5_2ORB_13BOOST_ham_bf.png)   / [HTML](/draws/scale/woman_5_2ORB_13BOOST_ham_bf.html)     |
| 5 | star-brisk-ham-bf | 0.8383 | [PNG](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.png)   / [HTML](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.html)  | [PNG](/draws/scale/woman_5_10STAR_3BRISK_ham_bf.png)  / [HTML](/draws/scale/woman_5_10STAR_3BRISK_ham_bf.html)    |

### Phase 2: Algorithm-Specific Champions

#### ORB Champions (Mean Efficiency: 0.7483 - Rank #1 Algorithm)

| Algorithm | Efficiency | Dataset | Visualization Links |
|-----------|------------|---------|-------------------|
| orb-orb-ham-bf    | 0.8821 | synthetic | [PNG](/draws/rot/woman_4_2ORB_2ORB_ham_bf.png)       / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html)      |
| orb-orb-ham-flann | 0.8789 | synthetic | [PNG](/draws/rot/woman_4_2ORB_2ORB_ham_flann.png)    / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_flann.html)   |
| orb-beblid-ham-bf | 0.8489 | drone     | [PNG](/draws/drone/17_2ORB_11BEBLID_ham_bf.png)      / [HTML](/draws/drone/17_2ORB_11BEBLID_ham_bf.html)     |
| orb-teblid-ham-bf | 0.8445 | synthetic | [PNG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.png)   / [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html)  |
| orb-boost-ham-bf  | 0.8412 | synthetic | [PNG](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.png)    / [HTML](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.html)   |

#### SIFT Champions (Mean Efficiency: 0.7191 - Rank #2 Algorithm)

| Algorithm | Efficiency | Dataset | Visualization Links |
|-----------|------------|---------|-------------------|
| akaze-sift-l2-bf      | 0.8092 | synthetic | [PNG](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.png)          / [HTML](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.html)           |
| akaze-sift-l2-flann   | 0.8064 | synthetic | [PNG](/draws/rot/woman_4_1AKAZE_0SIFT_l2_flann.png)       / [HTML](/draws/rot/woman_4_1AKAZE_0SIFT_l2_flann.html)        |
| sift-sift-l2-bf       | 0.8001 | synthetic | [PNG](/draws/rot/woman_4_0SIFT_0SIFT_l2_bf.png)           / [HTML](/draws/rot/woman_4_0SIFT_0SIFT_l2_bf.html)            |
| fast-sift-l2-bf       | 0.7717 | drone     | [PNG](/draws/drone/17_5FastFeatureDetector_0SIFT_l2_bf.png) / [HTML](/draws/drone/17_5FastFeatureDetector_0SIFT_l2_bf.html) |
| orb-sift-l2-bf        | 0.7670 | drone     | [PNG](/draws/drone/17_2ORB_0SIFT_l2_bf.png)               / [HTML](/draws/drone/17_2ORB_0SIFT_l2_bf.html)                |

### Phase 5: Unified Cross-Dataset Champions

| Algorithm | Avg Efficiency | Best Dataset Performance | Visualization Links |
|-----------|----------------|------------------------|-------------------|
| orb-beblid-ham-bf | Cross-Dataset Winner  | 0.8489 (drone) | [PNG](/draws/drone/17_2ORB_11BEBLID_ham_bf.png) / [HTML](/draws/drone/17_2ORB_11BEBLID_ham_bf.html) |
| orb-teblid-ham-bf | Cross-Dataset Runner-up | 0.8445 (synthetic) | [PNG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.png) / [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html) |
| orb-daisy-l2-bf   | Strong Unified | 0.8286 (drone) | [PNG](/draws/drone/17_2ORB_5DAISY_l2_bf.png) / [HTML](/draws/drone/17_2ORB_5DAISY_l2_bf.html) |
| gftt-daisy-l2-bf  | Consistent Unified | 0.8155 (drone) | [PNG](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.png) / [HTML](/draws/drone/17_8GFTTDetector_5DAISY_l2_bf.html) |
| orb-orb-ham-bf    | Synthetic Boost | 0.8821 (synthetic) | [PNG](/draws/rot/woman_4_2ORB_2ORB_ham_bf.png) / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| akaze-sift-l2-bf  | Reliable Unified | 0.8092 (synthetic) | [PNG](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.png) / [HTML](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.html) |

### Phase 6: Mobile Platform Optimized (Cross-Platform Consistency)

#### Oxford Mobile Champions (Desktop vs Mobile vs Mobile2)

| Algorithm | Desktop | Mobile | Mobile2 | Correlation | Visualization Links |
|-----------|---------|--------|---------|-------------|-------------------|
| orb-beblid-ham-bf | 0.6219 | 0.6229 | 0.6237 | 0.996 | [PNG](/draws/boat/2_2ORB_11BEBLID_ham_bf.png) / [HTML](/draws/boat/2_2ORB_11BEBLID_ham_bf.html) |
| orb-teblid-ham-bf | 0.6152 | 0.6168 | 0.6176 | 0.996 | [PNG](/draws/boat/2_2ORB_12TEBLID_ham_bf.png) / [HTML](/draws/boat/2_2ORB_12TEBLID_ham_bf.html) |
| orb-teblid-ham-flann | 0.6058 | 0.6065 | 0.6074 | 1.000 | [PNG](/draws/boat/2_2ORB_12TEBLID_ham_flann.png) / [HTML](/draws/boat/2_2ORB_12TEBLID_ham_flann.html) |

#### Synthetic Mobile Champions (Desktop vs Mobile vs Mobile2)

| Algorithm | Desktop | Mobile | Mobile2 | Correlation | Visualization Links |
|-----------|---------|--------|---------|-------------|-------------------|
| orb-orb-ham-bf | 0.8821 | 0.8811 | 0.8813 | 1.000 | [PNG](/draws/rot/woman_4_2ORB_2ORB_ham_bf.png) / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| orb-orb-ham-flann | 0.8789 | 0.8776 | 0.8778 | 1.000 | [PNG](/draws/rot/woman_4_2ORB_2ORB_ham_flann.png) / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_flann.html) |
| orb-teblid-ham-bf | 0.8445 | 0.8189 | 0.8194 | 0.994 | [PNG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.png) / [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html) |

### Phase 3: Component-Based Analysis

#### Best Detectors (Top Feature Detectors)

| Detector | Champion Combination | Efficiency | Visualization Links |
|----------|---------------------|------------|-------------------|
| ORB | orb-beblid-ham-bf | 0.7891 | [PNG](/draws/airsim/2_2ORB_11BEBLID_ham_bf.png) / [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_bf.html) |
| GFTT | gftt-daisy-l2-bf | 0.7436 | [PNG](/draws/airsim/2_8GFTTDetector_5DAISY_l2_bf.png) / [HTML](/draws/airsim/2_8GFTTDetector_5DAISY_l2_bf.html) |
| AKAZE | akaze-sift-l2-bf | 0.6809 | [PNG](/draws/airsim/2_1AKAZE_0SIFT_l2_bf.png) / [HTML](/draws/airsim/2_1AKAZE_0SIFT_l2_bf.html) |
| AGAST | agast-sift-l2-bf | 0.7359 | [PNG](/draws/airsim/2_7AgastFeatureDetector_0SIFT_l2_bf.png) / [HTML](/draws/airsim/2_7AgastFeatureDetector_0SIFT_l2_bf.html) |
| KAZE | kaze-sift-l2-bf | 0.7614 | [PNG](/draws/airsim/2_4KAZE_0SIFT_l2_bf.png) / [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_bf.html) |

#### Best Descriptors (Top Feature Descriptors)

| Descriptor | Champion Combination | Efficiency | Visualization Links |
|------------|---------------------|------------|-------------------|
| BEBLID | orb-beblid-ham-bf | 0.7891 | [PNG](/draws/airsim/2_2ORB_11BEBLID_ham_bf.png) / [HTML](/draws/airsim/2_2ORB_11BEBLID_ham_bf.html) |
| TEBLID | orb-teblid-ham-bf | 0.7782 | [PNG](/draws/airsim/2_2ORB_12TEBLID_ham_bf.png) / [HTML](/draws/airsim/2_2ORB_12TEBLID_ham_bf.html) |
| DAISY | gftt-daisy-l2-bf | 0.7436 | [PNG](/draws/airsim/2_8GFTTDetector_5DAISY_l2_bf.png) / [HTML](/draws/airsim/2_8GFTTDetector_5DAISY_l2_bf.html) |
| SIFT | akaze-sift-l2-bf | 0.6809 | [PNG](/draws/airsim/2_1AKAZE_0SIFT_l2_bf.png) / [HTML](/draws/airsim/2_1AKAZE_0SIFT_l2_bf.html) |
| ORB | orb-orb-ham-bf | 0.8821 | [PNG](/draws/rot/woman_4_2ORB_2ORB_ham_bf.png) / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| 4 | orb-boost-ham-bf | 0.8412 | [PNG](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.png) / [HTML](/draws/rot/woman_4_2ORB_13BOOST_ham_bf.html) | [PNG](/draws/scale/woman_5_2ORB_13BOOST_ham_bf.png) / [HTML](/draws/scale/woman_5_2ORB_13BOOST_ham_bf.html) |
| 5 | star-brisk-ham-bf | 0.8383 | [PNG](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.png) / [HTML](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.html) | [PNG](/draws/scale/woman_5_10STAR_3BRISK_ham_bf.png) / [HTML](/draws/scale/woman_5_10STAR_3BRISK_ham_bf.html) |

### Phase 3: Algorithm-Specific Champions

#### ORB Algorithm Top Performers

| Rank | Algorithm | Best Dataset | Efficiency | Visualization |
|------|-----------|--------------|------------|---------------|
| 1 | orb-orb-ham-bf | Synthetic | 0.8821 | [Rotation PNG](/draws/rot/woman_4_2ORB_2ORB_ham_bf.png) / [HTML](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| 2 | orb-beblid-ham-bf | Drone | 0.8489 | [Drone PNG](/draws/drone/17_2ORB_11BEBLID_ham_bf.png) / [HTML](/draws/drone/17_2ORB_11BEBLID_ham_bf.html) |
| 3 | orb-teblid-ham-bf | Synthetic | 0.8445 | [Rotation PNG](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.png) / [HTML](/draws/rot/woman_4_2ORB_12TEBLID_ham_bf.html) |
| 4 | orb-daisy-l2-bf | Drone | 0.8286 | [Drone PNG](/draws/drone/17_2ORB_5DAISY_l2_bf.png) / [HTML](/draws/drone/17_2ORB_5DAISY_l2_bf.html) |

#### SIFT-Based Top Performers

| Rank | Algorithm | Best Dataset | Efficiency | Visualization |
|------|-----------|--------------|------------|---------------|
| 1 | akaze-sift-l2-bf | Synthetic | 0.8092 | [Rotation PNG](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.png) / [HTML](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.html) |
| 2 | agast-sift-l2-bf | UAV | 0.7255 | [UAV PNG](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.png) / [HTML](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.html) |
| 3 | kaze-sift-l2-bf | AirSim | 0.7614 | [AirSim PNG](/draws/airsim/2_4KAZE_0SIFT_l2_bf.png) / [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_bf.html) |
| 4 | fast-sift-l2-bf | UAV | 0.7161 | [UAV PNG](/draws/uav/8_5FastFeatureDetector_0SIFT_l2_bf.png) / [HTML](/draws/uav/8_5FastFeatureDetector_0SIFT_l2_bf.html) |

#### AKAZE Algorithm Top Performers

| Rank | Algorithm | Best Dataset | Efficiency | Visualization |
|------|-----------|--------------|------------|---------------|
| 1 | akaze-sift-l2-bf | Synthetic | 0.8092 | [Rotation PNG](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.png) / [HTML](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.html) |
| 2 | akaze-vgg-l2-bf | Synthetic | 0.8192 | [Rotation PNG](/draws/rot/woman_4_1AKAZE_10VGG_l2_bf.png) / [HTML](/draws/rot/woman_4_1AKAZE_10VGG_l2_bf.html) |
| 3 | akaze-boost-ham-bf | Synthetic | 0.8182 | [Rotation PNG](/draws/rot/woman_4_1AKAZE_13BOOST_ham_bf.png) / [HTML](/draws/rot/woman_4_1AKAZE_13BOOST_ham_bf.html) |
| 4 | akaze-daisy-l2-bf | UAV | 0.7299 | [UAV PNG](/draws/uav/8_1AKAZE_5DAISY_l2_bf.png) / [HTML](/draws/uav/8_1AKAZE_5DAISY_l2_bf.html) |

#### FAST Algorithm Top Performers

| Rank | Algorithm | Best Dataset | Efficiency | Visualization |
|------|-----------|--------------|------------|---------------|
| 1 | fast-vgg-l2-bf | Drone | 0.7517 | [Drone PNG](/draws/drone/17_5FastFeatureDetector_10VGG_l2_bf.png) / [HTML](/draws/drone/17_5FastFeatureDetector_10VGG_l2_bf.html) |
| 2 | fast-sift-l2-bf | Drone | 0.7458 | [Drone PNG](/draws/drone/17_5FastFeatureDetector_0SIFT_l2_bf.png) / [HTML](/draws/drone/17_5FastFeatureDetector_0SIFT_l2_bf.html) |
| 3 | fast-daisy-l2-bf | Drone | 0.7271 | [Drone PNG](/draws/drone/17_5FastFeatureDetector_5DAISY_l2_bf.png) / [HTML](/draws/drone/17_5FastFeatureDetector_5DAISY_l2_bf.html) |
| 4 | fast-boost-ham-bf | Synthetic | 0.7101 | [Rotation PNG](/draws/rot/woman_4_5FastFeatureDetector_13BOOST_ham_bf.png) / [HTML](/draws/rot/woman_4_5FastFeatureDetector_13BOOST_ham_bf.html) |

#### BRISK Algorithm Top Performers

| Rank | Algorithm | Best Dataset | Efficiency | Visualization |
|------|-----------|--------------|------------|---------------|
| 1 | star-brisk-ham-bf | Synthetic | 0.8383 | [Rotation PNG](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.png) / [HTML](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.html) |
| 2 | akaze-brisk-ham-bf | Synthetic | 0.8016 | [Rotation PNG](/draws/rot/woman_4_1AKAZE_3BRISK_ham_bf.png) / [HTML](/draws/rot/woman_4_1AKAZE_3BRISK_ham_bf.html) |
| 3 | brisk-brisk-ham-bf | Synthetic | 0.7993 | [Rotation PNG](/draws/rot/woman_4_3BRISK_3BRISK_ham_bf.png) / [HTML](/draws/rot/woman_4_3BRISK_3BRISK_ham_bf.html) |
| 4 | brisk-daisy-l2-bf | UAV | 0.7234 | [UAV PNG](/draws/uav/8_3BRISK_5DAISY_l2_bf.png) / [HTML](/draws/uav/8_3BRISK_5DAISY_l2_bf.html) |

#### KAZE Algorithm Top Performers

| Rank | Algorithm | Best Dataset | Efficiency | Visualization |
|------|-----------|--------------|------------|---------------|
| 1 | kaze-sift-l2-bf | AirSim | 0.7614 | [AirSim PNG](/draws/airsim/2_4KAZE_0SIFT_l2_bf.png) / [HTML](/draws/airsim/2_4KAZE_0SIFT_l2_bf.html) |
| 2 | kaze-beblid-ham-bf | AirSim | 0.7502 | [AirSim PNG](/draws/airsim/2_4KAZE_11BEBLID_ham_bf.png) / [HTML](/draws/airsim/2_4KAZE_11BEBLID_ham_bf.html) |
| 3 | kaze-kaze-l2-bf | Synthetic | 0.7322 | [Rotation PNG](/draws/rot/woman_4_4KAZE_4KAZE_l2_bf.png) / [HTML](/draws/rot/woman_4_4KAZE_4KAZE_l2_bf.html) |
| 4 | kaze-vgg-l2-bf | AirSim | 0.7308 | [AirSim PNG](/draws/airsim/2_4KAZE_10VGG_l2_bf.png) / [HTML](/draws/airsim/2_4KAZE_10VGG_l2_bf.html) |

### Phase 4: Component Analysis

#### Top Feature Detectors (by Mean Efficiency Score)

| Rank | Detector | Mean Efficiency | Max Score | Std Dev | Total Tests | Visualization |
|------|----------|-----------------|-----------|---------|-------------|---------------|
| 1 | AKAZE | 0.5681 | 0.8092 | 0.1676 | 179 | [Best: akaze-sift-l2-bf](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.html) |
| 2 | ORB | 0.5473 | 0.8821 | 0.2044 | 163 | [Best: orb-orb-ham-bf](/draws/rot/woman_4_2ORB_2ORB_ham_bf.html) |
| 3 | STAR | 0.5298 | 0.8383 | 0.1740 | 165 | [Best: star-brisk-ham-bf](/draws/rot/woman_4_10STAR_3BRISK_ham_bf.html) |
| 4 | AGAST | 0.4934 | 0.7497 | 0.1698 | 165 | [Best: agast-sift-l2-bf](/draws/uav/8_7AgastFeatureDetector_0SIFT_l2_bf.html) |
| 5 | BRISK | 0.4880 | 0.7993 | 0.1856 | 164 | [Best: brisk-brisk-ham-bf](/draws/rot/woman_4_3BRISK_3BRISK_ham_bf.html) |

#### Top Feature Descriptors (by Mean Efficiency Score)

| Rank | Descriptor | Mean Efficiency | Max Score | Std Dev | Total Tests | Visualization |
|------|------------|-----------------|-----------|---------|-------------|---------------|
| 1 | SIFT | 0.6471 | 0.8092 | 0.0907 | 129 | [Best: akaze-sift-l2-bf](/draws/rot/woman_4_1AKAZE_0SIFT_l2_bf.html) |
| 2 | DAISY | 0.6321 | 0.8286 | 0.1014 | 140 | [Best: orb-daisy-l2-bf](/draws/drone/17_2ORB_5DAISY_l2_bf.html) |
| 3 | VGG | 0.6155 | 0.8367 | 0.1141 | 140 | [Best: orb-vgg-l2-bf](/draws/rot/woman_4_2ORB_10VGG_l2_bf.html) |
| 4 | KAZE | 0.6091 | 0.7341 | 0.1431 | 11 | [Best: kaze-kaze-l2-bf](/draws/rot/woman_4_4KAZE_4KAZE_l2_bf.html) |
| 5 | AKAZE | 0.6042 | 0.8121 | 0.0912 | 30 | [Best: akaze-akaze-ham-bf](/draws/rot/woman_4_1AKAZE_1AKAZE_ham_bf.html) |

## Citation

```bibtex
@phdthesis{elmas2025uav,
    title={Towards Efficient 3D Reconstruction from UAV Imagery: Evaluation of OpenCV Feature Detection, Description and Matching Combinations},
    author={Elmas, Abbas},
    year={2026},
    school={Çukurova University},
    type={PhD Thesis}
}
```
