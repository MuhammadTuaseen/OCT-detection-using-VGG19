# VGG19
Retinal Optical Coherence Tomography (OCT)usingVGG19
Retinal Optical Coherence Tomography (OCT) Images: Unveiling the Inner Workings of the Eye

Optical coherence tomography (OCT) has revolutionized ophthalmology by providing high-resolution, cross-sectional images of the retina, the innermost layer of the eye responsible for vision. This non-invasive imaging technique utilizes the principles of interferometry to capture detailed information about the retina's intricate structure, enabling the diagnosis and monitoring of a wide range of eye conditions. Real-life applications of retinal OCT are numerous. In the diagnosis of age-related macular degeneration (AMD), a leading cause of vision loss in older adults, OCT can detect subtle changes in the retinal layers, such as thinning or fluid accumulation, which may indicate early signs of the disease. This early detection allows for timely intervention with treatment options that can slow disease progression and preserve vision. Similarly, OCT plays a crucial role in monitoring diabetic retinopathy, a complication of diabetes that can lead to vision loss. OCT can reveal abnormalities in the retinal blood vessels, such as microaneurysms and hemorrhages, providing a valuable tool for assessing the severity of diabetic retinopathy and guiding treatment decisions. OCT technology has also extended beyond diagnosis to aid in surgical planning and monitoring. In the treatment of retinal detachment, OCT can precisely visualize the detached retina, guiding the surgeon in placing laser burns to reattach the retina and restore vision. Similarly, in cataract surgery, OCT can assess the health of the retina and underlying structures before and after cataract removal, ensuring optimal surgical outcomes. Retinal OCT has become an indispensable tool in ophthalmic practice, providing unparalleled insights into the intricate structure and function of the retina. Its non-invasive nature, high resolution, and ability to capture dynamic processes make it a powerful diagnostic and monitoring tool for a wide range of eye conditions. As OCT technology continues to evolve, its applications in ophthalmology are bound to expand, further enhancing our ability to preserve and restore vision.

DETAILS OF DATASET:

TOTAL SIZE: Found 84484 files belonging to 3 classes. TRAINING SIZE: Found 83484 images belonging to 4 classes. VALIDATION SIZE:Found 32 images belonging to 4 classes. TESTING SIZE: Found 968 images belonging to 4 classes.

loss: 0.1243 accuracy: 0.9607 auc: 0.9972 cohen_kappa: 0.9477 f1_score: 0.9607 precision: 0.9666 recall: 0.9576

            precision   recall    f1-score   support
     CNV       0.31      0.33      0.32       242
     DME       0.20      0.19      0.19       242
  DRUSEN       0.22      0.22      0.22       242
  NORMAL       0.28      0.29      0.28       242

accuracy                           0.26       968

macro avg 0.25 0.26 0.25 968 weighted avg 0.25 0.26 0.25 968

Class 0: True Positives: 81 False Positives: 182 True Negatives: 544

False Negatives: 161
Class 1: True Positives: 45 False Positives: 177 True Negatives: 549

False Negatives: 197
Class 2: True Positives: 53 False Positives: 185 True Negatives: 541

False Negatives: 189
Class 3: True Positives: 69 False Positives: 176 True Negatives: 550

False Negatives: 173
