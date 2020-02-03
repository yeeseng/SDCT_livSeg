# SDCT_livSeg
Comparison exam between SDCT and conventional CT for liver segmentation
# Introduction
Liver segmentation and volumetry have traditionally been performed using computed tomography (CT) attenuation to discriminate
liver from other tissues. In this project, we evaluated if spectral detector CT (SDCT) can improve liver segmentation over conventional CT on 2 segmentation methods.
# Materials and Methods
In this Health Insurance Portability and Accountability Act–compliant institutional review board–approved retrospective
study, 30 contrast-enhanced SDCT scans with healthy livers were selected. The first segmentation method is based on Gaussian mixture models of the SDCT data. The second method is a convolutional neural network–based technique called U-Net. Both methods were compared against equivalent algorithms, which used conventional CT attenuation, with hand segmentation as the reference standard. Agreement to the reference standard was assessed using Dice similarity coefficient.
# Results 
Dice similarity coefficients to the reference standard are 0.93 ± 0.02 for the Gaussian mixture model method and 0.90 ± 0.04 for the CNN-
based method (all 2 methods applied on SDCT). These were significantly higher compared with equivalent algorithms applied on conventional CT, with Dice coefficients of 0.90 ± 0.06 (P = 0.007) and 0.86 ± 0.06 (P < 0.001), respectively.
# Conclusion
On both liver segmentation methods tested, we demonstrated higher segmentation performance when the algorithms are applied on SDCT data compared with equivalent algorithms applied on conventional CT data.
