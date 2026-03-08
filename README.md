# Kyoto Station Crowd Flow Analysis

## Overview

This project analyzes pedestrian flow around Kyoto Station using a fixed camera video.

The goal is to determine which of the following hypotheses better explains congestion near the station plaza.

- **Hypothesis A (Train-origin flow)**  
  People exiting the station building create congestion.

- **Hypothesis B (Bus-origin flow)**  
  People moving from the bus terminal toward the station create congestion.

To evaluate these hypotheses, this project measures directional pedestrian flow using **optical flow analysis**.

---

# Method

The analysis consists of three main steps.

## 1. Observation Zone Design

Instead of analyzing the entire image, the analysis focuses on a **central horizontal band** where most pedestrian crossings occur.

This reduces the influence of unrelated background motion.
