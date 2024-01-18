# nps_uw_multibeam_sonar
Multibeam sonar plugin with NVIDIA Cuda library

# Experiment_old_acoustic_msgs Branch

- Based on `13a30b7f1a52413dc7a97935a2260ba645188f10` of nps_uw_multibeam_sonar

Uses old `acoustic_msgs` package
- `git checkout 8a053bd4d14955363940e63c14e646d28da75504` at `marine_msgs` repository


To record
```
rosbag record -O Record.bag -l 1 /oculus_m1200d/sonar_image_raw
```

# Wiki
https://field-robotics-lab.github.io/dave.doc/contents/dave_sensors/Multibeam-Forward-Looking-Sonar/
