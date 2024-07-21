# Vis-OCT-Dehazenet

RVO Annual Meeting Abstract  |   June 2022
Dehazing of Visible-light OCT B-scans using deep neural model improves visualization and quantification of retinal sub-layers.
Zeinab Ghassabi; Joel S Schuman; TingFang Lee; Eitan Shemuelian; Ronald Zambrano; Roman Kuranov; Ian Rubinoff; Gadi Wollstein; Hao Zhang; Hiroshi Ishikawa

Abstract
Purpose : Multiple sublayers of retina can be visualized with visible light (vis-) OCT.However, image quality can be compromised due to patient movement, cataracts, small pupil size, and light scattering causing haziness and variability in signal to noise ratio in individual A-scans and in entire B-scans.The purpose of this study was to examine the effect of conventional and deep neural network dehazing techniques on the visibility and quantitative assessment of retinal sub-layers on vis-OCT images.

Methods : 9 healthy and 5 glaucoma subjects were scanned 3 times during one session.Scanning was done on the superior nasal side of para-foveal region,1.5 mm from the fovea with a 3D speckle reduction raster scanning protocol(3x3x1.6 mm with 8192x16x1024 samplings) using a prototype vis-OCT system.16 A-scan lines were averaged to reduce speckle noise.Gray-scale image dehazing guided by depth information and pretrained Dehazenet deep model following deep convolutional neural network with residual learning(DnCNN) were applied on original B-scans.Quality improvement were evaluated using quality index(QI) and contrast to noise ratio(CNR) on dehazed B-scans.For each subject, the dehazed B-scan of Dehazenet and DnCNN from a fixed location adjacent to the fovea were selected.The distances between each of 3 bright inner plexiform layers(IPL) and retinal pigment epithelium(RPE) sublayers were segmented manually for thickness measurements using a 8 A-scan averaged profile(Fig.).Coefficient of variations (CVs) were calculated to assess the measurement repeatability of the sublayers on original and dehazed B-scans.

Results : Healthy and glaucoma subjects were age 45.67±11.7and 59.60±13.4(p=0.07,t-test),visual field mean deviation(MD)-1.55 to1.20 dB,and from -26.42 to -7.70dB(p= 0.003,Wilcoxon),global mean circumpapillary retinal nerve fiber layer(RNFL)thickness 96.33±12.20 and 59.80±9.09mm(p<0.001,Wilcoxon),respectively.Dehazed B-scans obtained by deep models have statistically significant better QI and CNR(Table1).Overall intra-subject CVs showed significantly improved reproducibility on all measured sub-layers of dehazed B-scans compared to original scans for all subjects(Tables 2,3).

Conclusions : Vis-OCT image quality can be improved using deep neural network dehazing model resulting in higher reproducible thickness measurements of retinal sublayers within subjects in dehazed B-scans.

This abstract was presented at the 2022 ARVO Annual Meeting, held in Denver, CO, May 1-4, 2022, and virtually.
