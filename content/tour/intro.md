---
widget: "blank"
headless: true

weight: 10
title: "**The iLoc workshop** - \\

High-integrity Localization for Automated Vehicles"
subtitle:
active: true

design:
    columns: "1"
#    background:
#      gradient_end: '#1976d2'
#      gradient_start: '#004ba0'
#      gradient_angle: 180
    text_color_light: true
---
The iLoc workshop aims to address the localization integrity requirements of automated vehicles. The concept of integrity is defined as “a measure of trust which can be placed in the correctness of the information supplied by the total system”. In particular, it is a critical performance indicator for the navigation of highly automated vehicles (e.g., SAE L3 and above). To guarantee the safe driving of an AV in varying environments, measures of the localization information gathered from different sensors, such as LiDAR, IMU and GNSS, are required. Continuously and reliably estimating a vehicle’s position in varying driving environments is essential for autonomous driving and safe operation. However, dynamic and complex traffic environments make high-integrity localization very challenging in the vehicular domain. In our 2nd iLoc workshop, we want to emphasize the importance of integrity in ITS and address the scientific challenges in managing localization integrity for vehicle navigation in complex traffic environments, including its use as part of perception tasks.
### Research Questions of Interest:
- What are the <span style="color: DodgerBlue;">leading factors</span> for high-integrity localization for AVs, e.g., road geometry, vehicle dimension, sensor accuracy, environmental factors, vehicle motion, and other road users?
- Which multi-sensor architectures and data fusion methods are best suited for autonomous driving? 
- How to estimate the <span style="color: DodgerBlue;">uncertainty</span> and <span style="color: DodgerBlue;">integrity risks</span> applicable to model-based and data-driven approaches to localization?
- How can <span style="color: DodgerBlue;">maps</span> be used to increase localization integrity?
- How to combine a vehicle kinematic model and road geometry to improve integrity estimation? Is the sequence of AV’s maneuver tasks of driving from position A to B well defined?
- What are the <span style="color: DodgerBlue;">integrity metrics</span> needs for AVs? That is, in longitudinal, lateral, vertical (e.g., multi-level road interchanges), orientation (pitch, roll, and yaw angles).
- Are there any <span style="color: DodgerBlue;">emergent standards</span> applicable to the estimation of integrity in the Intelligent Transportation field?
- How to verify experimentally the system localization integrity when considering low risks? E.g., down to 10e-5 or below, and under numerous driving conditions?
  
### Topics of Interest:
- Uncertainty propagation and updates while an AV drives in different environments.
- Novel algorithm and requirement definition for integrity, continuity, availability, and accuracy evaluation for intelligent transportation
- Map reference with its own integrity measure, including 2D digital map, high-definition map, 3D map/3D city model, even more precise survey map with both dynamic and static objects.
- Quantification and representation of the models’ aleatoric (or statistical) and epistemic (or systematic) uncertainties for both environmental perception and localization.
- Uncertainty estimation of LiDAR point clouds registration and imagery data processing in e.g., probabilistic and deep learning-based models.
- State-of-the-art deep learning multi-modal data fusion for e.g., GNSS, LiDAR point clouds, images, 3D map localization information with integrity estimation.
