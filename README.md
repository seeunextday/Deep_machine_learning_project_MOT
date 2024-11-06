# Project Title: A Study of TransTrack for Multi-Object Tracking and Its Robustness Evaluation

## Introduction
This project is a study on Multi-Object Tracking (MOT) based on TransTrack. It examines the robustness of TransTrack under various adverse conditions such as poor lighting, motion blur, and snow.

### Key Features:
- **Why TransTrack?**: Investigates the advantages of using a transformer-based architecture for MOT.
- **Performance Evaluation**: Evaluates performance in challenging environments and highlights the strengths and limitations of TransTrack.
- **Dataset**: We augmented the MOT17 dataset and used transfer learning to improve tracking accuracy.
- **Results**:
  - Strengths: Effective tracking under diverse real-world conditions.
  - Limitations: Challenges under adverse conditions.

These insights aim to provide directions for future improvements in multi-object tracking systems.

## Architecture
The architecture of TransTrack uses a transformer-based model with two decoders: one for detecting new objects and another for tracking previously detected ones. This helps in enhancing tracking accuracy across frames, especially under occlusion and changing scenarios.

## Adverse Conditions Evaluation
The project also focused on assessing the performance of TransTrack in environments with:
- **Lighting Effects**
- **Snow Effects**
- **Motion Blur**

Performance metrics such as MOTA and IDP recall were analyzed before and after applying transfer learning techniques.

## Pipeline Development
The entire development pipeline used in the project is represented below:

## Performance Metrics
The metrics to evaluate performance include:
- **IDP Recall**
- **MOTA (Multi-Object Tracking Accuracy)**
- **IDs Tracking**

After applying transfer learning, the model's performance was compared against its initial results to illustrate the impact.

## References
- G. Ciaparrone, F. Luque Sánchez, S. Tabik, L. Troiano, R. Tagliaferri, and F. Herrera, “Deep learning in video multi-object tracking: A survey,” *Neurocomputing*, vol. 381, pp. 61-88, 2020.
- P. Sun, J. Cao, Y. Jiang, R. Zhang, E. Xie, Z. Yuan, C. Wang, and P. Luo, “TransTrack: Multiple-Object Tracking with Transformer,” arXiv preprint arXiv:2012.15460, 2020.

