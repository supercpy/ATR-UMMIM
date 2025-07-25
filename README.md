# ATR-UMMIM Dataset

**ATR-UMMIM** (Unmanned Multimodal Image Matching) is a large-scale dataset for multimodal image registration and matching in aerial scenarios. It focuses on aligning visible and infrared image pairs captured by UAVs under diverse real-world conditions. This dataset is designed to advance research in multimodal image alignment, fusion-based detection, and condition-aware visual understanding.

## 📂 Dataset Overview

- **Modalities**: Aligned visible–infrared image pairs
- **Scene Count**: 15,000+ unique locations
- **Total Images**: 60,000+ (30k visible, 30k infrared)
- **Resolution**: 640×512 pixels
- **Annotations**:
  - Coarse-level manual alignment
  - Fine-level keypoints (for subset)
  - Detailed condition labels (see below)

## 🌦 Condition Annotations

To reflect real-world complexity, each image pair is annotated across six condition attributes:

- **Altitude**: 80m–300m (majority in 100–120m)
- **Camera Angle**: 0° (nadir) to 75° (oblique), majority at 30°–45°
- **Shooting Time**: Day, night, dawn, morning, afternoon
- **Weather**: Sunny, cloudy, rainy, after-rain, foggy
- **Illumination**: Night, twilight, dim, normal, overexposed
- **Scenario**: 11 types including urban, suburban, village, factory, road, school, etc.

This rich condition diversity enables robust evaluation of multimodal models under dynamic imaging environments.


## 🖼 Example Images

<p align="center">
  <img src="assets/example_pair_1.jpg" width="45%"/>
  <img src="assets/example_pair_2.jpg" width="45%"/>
</p>

## 🔗 Download

**[⏬ Dataset Download Link ([Link](https://pan.baidu.com/s/1E37Vdzzu4WMUFDGeF6G6ww))]**

> Please fill in the download address or contact us for access.

## 📊 Applications

- Multimodal image registration and alignment
- Condition-aware image matching
- Cross-modality fusion and detection
- UAV-based remote sensing tasks

## 📄 Citation

If you use ATR-UMMIM in your research, please cite:

```bibtex
@misc{ATRUMMIM2025,
  title={ATR-UMMIM: A Multimodal UAV Image Matching Dataset under Diverse Conditions},
  author={Your Name and Others},
  year={2025},
  howpublished={\url{https://github.com/yourname/ATR-UMMIM}},
}
