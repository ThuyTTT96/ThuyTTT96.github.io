---
layout: page
title: MOEMO - Online Learning Analytics Dashboard
description: Real-time emotion and attention detection system for online learning environments
img: assets/img/project_moemo.jpg
importance: 7
category: tools
---

## Overview

Developed at Hosei University, MOEMO is a real-time learning analytics dashboard designed to detect and visualize student engagement, emotion, and attention in online learning environments.

### Key Features

- **Engagement Detection**: Built using MTCNN (Multi-task Cascaded Convolutional Networks) for face detection
- **Emotion Recognition**: Implemented Mini-Xception model for real-time emotion classification
- **Attention Tracking**: Monitored student attention levels during online sessions
- **Dashboard Visualization**: Interactive dashboard for educators to monitor class engagement

### System Architecture

```
Video Stream → Face Detection (MTCNN) → Emotion Recognition (Mini-Xception)
                                              ↓
                                    Dashboard Visualization
```

### Technologies Used

- **Face Detection**: MTCNN
- **Emotion Model**: Mini-Xception
- **Backend**: Python
- **Visualization**: Web-based dashboard
- **Framework**: TensorFlow/Keras

### Publications

This work contributed to multiple publications:
1. "Students' Emotion extraction and visualization for engagement detection in online learning" - *KES 2021*
2. "A Real-Time Learning Analytics Dashboard for Automatic Detection of Online Learners' Affective States" - *Sensors 2023*

### Impact

The system helps educators understand student engagement in remote learning settings, enabling timely interventions to improve learning outcomes.

